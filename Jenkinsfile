pipeline {
    agent { label "docker" }
    stages {
        stage('CI') {
            steps {
                git 'https://github.com/mahmoud254/jenkins_nodejs_example'
                withCredentials([usernamePassword(credentialsId: 'Dockerhub', usernameVariable: 'USER', passwordVariable: 'PASS')]) {
                    sh "docker build . -f dockerfile -t ${USER}/node-app:v1"
                    sh "docker login -u ${USER} -p ${PASS}"
                    sh "docker push ${USER}/node-app:v1"
                }
            }
        }
        stage('CD') {
            steps {
                withCredentials([usernamePassword(credentialsId: 'Dockerhub', usernameVariable: 'USER', passwordVariable: 'PASS')]) {
                    sh "docker login -u ${USER} -p ${PASS}"
                    sh "docker run -d -p 3000:3000 ${USER}/node-app:v1"
                }
            }
        
            post {
            success {
                slackSend ( message: "Hello from jenkins pipeline, CI and CD are run successfuly")
            }
            
            failure {
                slackSend ( message: "Hello from jenkins pipeline, CI and CD are failled to run")
            }
        }    
        }

    }
}
