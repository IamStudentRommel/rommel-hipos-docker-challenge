### Challenge 2 - NodeJS application

#### Steps

- Use the folder challenge2.
- Extract the files present on challenge2.zip to the challenge’s root folder.
- Create a Dockerfile to build the server’s Docker container.

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/12bcee0a-6ac0-405b-beeb-819e52e47353)

- Create the Docker compose file using NGinx and the API server from the previous step.
- NGinx should listen on port 8080.

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/0556bb8f-797e-4e93-b367-247d916a7b23)

Command to build the image: `docker build -t <name of the image> .`

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/39b4ed9c-08c8-4a6a-aa9f-a699405a75b1)

Once the build is successfully executed, open the Docker desktop to view the image created.

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/d3d172bf-779c-48a1-bdd5-4ef900893f41)

Run the image to generate the container and set the port to 8080

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/6f67d741-a96a-4d40-8b06-cb8f80a51d65)

Now it’s ready to run inside the container! 🎉🎉🎉

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/68ee88af-6490-4b72-b7ec-2fa79c9d479b)
