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
![Screenshot from 2023-01-28 17-51-46](https://user-images.githubusercontent.com/40915944/215354373-7f9ddf89-81f5-4686-ab51-1ef24147ec37.png)
![Screenshot from 2023-01-28 17-53-09](https://user-images.githubusercontent.com/40915944/215354383-71e761a9-85b6-4be3-9b17-2fe04c6e3529.png)


#################
1- create docker file to build image for jenkins slave

![image](https://user-images.githubusercontent.com/40915944/215353832-2333fc91-bd97-4644-be80-b00059a800d9.png)

2- create container from this image and configure ssh

![image](https://user-images.githubusercontent.com/40915944/215353972-78d3041d-2796-4b76-95ee-4e89ee49f04f.png)
![image](https://user-images.githubusercontent.com/40915944/215354006-9ef119f5-0710-47b9-901c-73d677475e12.png)
![image](https://user-images.githubusercontent.com/40915944/215291139-2158b85f-dd48-45bf-9f5d-a45fc0d41e9a.png)

3 from jenkins master create new node with the slave container

![image](https://user-images.githubusercontent.com/40915944/215354472-f46af224-679f-43e9-bddd-36f8f8b19e20.png)
![image](https://user-images.githubusercontent.com/40915944/215354488-48a0e58f-fd40-4239-a4ef-3ec211479507.png)
![image](https://user-images.githubusercontent.com/40915944/215354538-61e8519e-67a6-44fa-9589-7c079d459dd5.png)
![image](https://user-images.githubusercontent.com/40915944/215354562-a65b96ee-2d15-4b2d-9b29-ffbcb39176ad.png)

4- integrate slack with jenkins
5- send slack message when stage in your pipeline is successful
6- install audit logs plugin and test it
7- fork the following repo https://github.com/mahmoud254/Booster_CI_CD_Project and add dockerfile to run this django app and use github actions to build the docker image and push it to your dockerhub
