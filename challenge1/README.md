### Challenge 1 - Simple static page server

#### Steps

- Use the folder challenge1.
- Add a "public" folder with some assets.
- Add a file with the name index.html. It should contain your name and SAIT ID in the contents.
- ![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/06995393-956a-4a5f-94de-05a7635a1a55)

- Create a Dockerfile to use NGinx to serve pages existent in the public folder.
- Create the Docker image.
- Execute docker with the right parameters.

Command to build the image: `docker build -t <name of the image> .`

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/29c6c53b-507d-4173-8d85-60d11c4abd91)

Once the build is successfully executed, open the Docker desktop to view the image created.

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/bb7d423b-d008-4775-b277-3138aff38f75)

Run the image to generate the container and set the port to 8080

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/1598920f-c395-4fd6-9165-2caa57cd6e5e)

Now it’s ready to run inside the container! 🎉🎉🎉

![image](https://github.com/IamStudentRommel/rommel-hipos-docker-challenge/assets/156134777/b9e3f994-2025-4825-9481-ce2466a2ce78)
