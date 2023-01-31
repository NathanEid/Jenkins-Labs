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

![image](https://user-images.githubusercontent.com/40915944/215832932-6ad62f2a-2cab-4419-b38a-669cb859f4b1.png)
![image](https://user-images.githubusercontent.com/40915944/215837654-9a8c2ec4-7224-4ad0-89e4-a45e055174cd.png)

2- create container from this image and configure ssh

![image](https://user-images.githubusercontent.com/40915944/215840377-bccc72cf-03bc-454b-b3f6-e72deefd4a87.png)

3 from jenkins master create new node with the slave container

![image](https://user-images.githubusercontent.com/40915944/215841757-6222e364-be7b-4f22-bc78-6a14e9219b2b.png)
![image](https://user-images.githubusercontent.com/40915944/215842233-e4400b10-2ac7-4f37-8795-65573ed8b5f3.png)
![image](https://user-images.githubusercontent.com/40915944/215842353-4d4c2221-2d18-4083-88ba-d0c6035a287f.png)
![image](https://user-images.githubusercontent.com/40915944/215842485-5ebcd2ea-9d02-44a0-a6fd-3e5bcf2aa345.png)
![image](https://user-images.githubusercontent.com/40915944/215842698-4c33c521-caef-4c0f-b289-893ec6d88003.png)
![image](https://user-images.githubusercontent.com/40915944/215843132-a7b3c629-32dd-434b-b40e-4741ae2c01bd.png)
![image](https://user-images.githubusercontent.com/40915944/215843674-6c6f62ae-b4b9-4728-9048-bab7c4fdbadc.png)
![image](https://user-images.githubusercontent.com/40915944/215843449-14475135-8423-458a-8597-5f5f1d0e6215.png)
![image](https://user-images.githubusercontent.com/40915944/215843508-8ba0518c-a067-4691-bc19-802e89afc840.png)
![image](https://user-images.githubusercontent.com/40915944/215845473-4ec7c878-9b71-4cdf-838d-4dc2c3f23e44.png)
![image](https://user-images.githubusercontent.com/40915944/215843855-10c265ea-5694-480c-9ad8-9cb77dcdd182.png)

4- integrate slack with jenkins

![image](https://user-images.githubusercontent.com/40915944/215874135-998896ec-92fd-40f1-8251-605901cc7a19.png)
![image](https://user-images.githubusercontent.com/40915944/215874189-f4ba45c6-780d-47ae-89b1-fee0552701aa.png)
![image](https://user-images.githubusercontent.com/40915944/215875465-44927a41-f00c-4627-89a3-1e7e0673c012.png)
![image](https://user-images.githubusercontent.com/40915944/215877868-118934c8-3391-41ba-85b6-5266be4d9fc8.png)
![image](https://user-images.githubusercontent.com/40915944/215877919-1b3aa990-936a-4f21-84e5-9e079a1570bf.png)

5- send slack message when stage in your pipeline is successful

![image](https://user-images.githubusercontent.com/40915944/215888233-8db9d00a-1042-42a1-a963-daea315e3042.png)
![image](https://user-images.githubusercontent.com/40915944/215888325-3590950b-c859-45bf-8e91-7f4f74bcd18b.png)
![image](https://user-images.githubusercontent.com/40915944/215888405-aeddb6b9-aeab-4da5-a7ec-764e60d4890e.png)

6- install audit logs plugin and test it

![image](https://user-images.githubusercontent.com/40915944/215889046-7c372ec3-0215-4ed7-80ff-e4a1848250f7.png)
![image](https://user-images.githubusercontent.com/40915944/215889129-b42212be-472f-45cb-a182-51f168022729.png)
![image](https://user-images.githubusercontent.com/40915944/215889656-5b507293-1537-42cb-a7f4-474e9cc76e60.png)
![image](https://user-images.githubusercontent.com/40915944/215889694-6a2f1f6b-9318-4923-ac43-5a8107ed5e47.png)

7- fork the following repo https://github.com/mahmoud254/Booster_CI_CD_Project and add dockerfile to run this django app and use github actions to build the docker image and push it to your dockerhub
