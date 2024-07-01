# docker-challenge-template
### Docker Introduction
Docker is an open-source platform that allows you to automate the deployment, scaling, and management of applications using containerization. Containers are lightweight, portable units that encapsulate an application and all its dependencies, ensuring that the application runs consistently across different environments

### Importance of Docker in Software Development
Using Docker Desktop facilitates teamwork by enabling one-click sharing of work via Git or Docker Hub. Additionally, it features an intuitive user interface (UI) for numerous common tasks, such as initiating, pausing, and ending containers. Through our Docker Community Slack channel, users of Docker may also communicate, learn from, and work together with one another. By leveraging Docker's powerful containerization technology, developers can streamline their workflows, enhance collaboration, and ensure that applications run reliably in any environment.

Additionally, Docker users can learn, connect, and collaborate with each other via our Docker Community Slack channel. We can chat with Docker community leaders, Docker Captains, and your fellow local developers in the channel

### Challenge 1 - Simple static page server
#### Steps
* Use the folder challenge1.
* Add a "public" folder with some assets.
* Add a file with the name index.html. It should contain your name and SAIT ID in the contents.
* 
  ![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/06995393-956a-4a5f-94de-05a7635a1a55)

* Create a Dockerfile to use NGinx to serve pages existent in the public folder.
*	Create the Docker image.
*	Execute docker with the right parameters.

Command to build the image: `docker build -t <name of the image> .`

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/29c6c53b-507d-4173-8d85-60d11c4abd91)

Once the build is successfully executed, open the Docker desktop to view the image created.

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/bb7d423b-d008-4775-b277-3138aff38f75)

Run the image to generate the container and set the port to 8080

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/1598920f-c395-4fd6-9165-2caa57cd6e5e)

Now it’s ready to run inside the container! 🎉🎉🎉

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/b9e3f994-2025-4825-9481-ce2466a2ce78)


### Challenge 2 - NodeJS application
#### Steps
*	Use the folder challenge2.
*	Extract the files present on challenge2.zip to the challenge’s root folder.
*	Create a Dockerfile to build the server’s Docker container.
  
![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/12bcee0a-6ac0-405b-beeb-819e52e47353)

*	Create the Docker compose file using NGinx and the API server from the previous step.
*	NGinx should listen on port 8080.
  
  ![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/0556bb8f-797e-4e93-b367-247d916a7b23)

Command to build the image: `docker build -t <name of the image> .`

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/39b4ed9c-08c8-4a6a-aa9f-a699405a75b1)

Once the build is successfully executed, open the Docker desktop to view the image created.

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/d3d172bf-779c-48a1-bdd5-4ef900893f41)

Run the image to generate the container and set the port to 8080

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/6f67d741-a96a-4d40-8b06-cb8f80a51d65)

Now it’s ready to run inside the container! 🎉🎉🎉

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/68ee88af-6490-4b72-b7ec-2fa79c9d479b)





  



