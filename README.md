# Jenkins-Day-02

### Lab 02

4- configure jenkins image to run docker commands on your host docker daemon

![image](https://user-images.githubusercontent.com/40915944/215272859-41336994-a422-4079-9ab8-53ce2edba385.png)
![image](https://user-images.githubusercontent.com/40915944/215272903-f1b71b7a-32fb-4734-bf97-3322e5fb90ea.png)
![image](https://user-images.githubusercontent.com/40915944/215272931-4d798bc4-2759-41fc-a635-f3f2ab430a03.png)
![image](https://user-images.githubusercontent.com/40915944/215273210-7f694cd3-456a-4d01-9b28-17402209b064.png)

5- create CI/CD for this repo https://github.com/mahmoud254/jenkins_nodejs_example.git

![image](https://user-images.githubusercontent.com/40915944/215273800-0638cd3e-edda-486f-9b7e-e18ddb2a37e6.png)
![image](https://user-images.githubusercontent.com/40915944/215273886-f25a6d14-e9f1-4e0f-b4c8-8c61ce2a3f4a.png)
![image](https://user-images.githubusercontent.com/40915944/215276015-f85d7046-2819-42d4-bcfe-deb84698e097.png)
![image](https://user-images.githubusercontent.com/40915944/215276059-f72be395-f05d-43ae-abcf-ae29ec37dd7b.png)
![image](https://user-images.githubusercontent.com/40915944/215276101-b805d9e7-65f8-4ccc-896e-cd98cea13851.png)
![image](https://user-images.githubusercontent.com/40915944/215276166-72c3decb-4f7b-4a7c-a151-1a5a5400a237.png)

#################
1- create docker file to build image for jenkins slave
2- create container from this image and configure ssh 
3 from jenkins master create new node with the slave container
4- integrate slack with jenkins
5- send slack message when stage in your pipeline is successful
6- install audit logs plugin and test it
7- fork the following repo https://github.com/mahmoud254/Booster_CI_CD_Project and add dockerfile to run this django app and use github actions to build the docker image and push it to your dockerhub
