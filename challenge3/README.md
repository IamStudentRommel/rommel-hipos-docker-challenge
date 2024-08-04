
### Challenge 3 - Full-Stack Application with Docker

### DB Setup.
1.	Create the environmental variable (.env) to store your DB parameters and make sure the configuration is aligned with your local DB connection.
   
     ![image](https://github.com/user-attachments/assets/4543918b-cd0f-488e-8f87-b5919231907f)


2.	Now create the schema and needed table for the books, then load the required records based on the given “init.sql”

  	 ![image](https://github.com/user-attachments/assets/477f2dd4-568b-4eaf-92e3-b92953223cf6)

### API Setup.
1.	Navigate to challenge3 folder and perform “npm install” to initialize the required modules.

  	![image](https://github.com/user-attachments/assets/999c0dcb-b283-4c5d-99b6-18d0e8ab9927)

3.	Ensure to install the “dotenv” package if haven’t done yet.

  	![image](https://github.com/user-attachments/assets/5112beaa-e57b-46f0-876c-a6eda752860c)

5.	Now check if all services are running properly. Using your browser, access the address. If the result is not expected, then return and fix it.

    http://localhost:3000/api/books

    ![image](https://github.com/user-attachments/assets/e19a94f0-6b3f-4cb9-b6eb-403e86dc3a99)

    http://localhost:3000/api/books/1

    ![image](https://github.com/user-attachments/assets/5bc59a42-61e2-4ef2-bb00-21e8d21f0417)

4.	Finally create the “docker-compose.yml” which will be used as the configuration service when the image is created in Docker.

     ![image](https://github.com/user-attachments/assets/bf86ed71-dee1-4d58-8a2e-78f7814e292f)

### Working with Docker.

1.	Execute the created docker-compose.yml using “docker-compose up” command.
   
     ![image](https://github.com/user-attachments/assets/77ecc1c6-7494-45f0-b359-389cb041c80d)

2.	Execute command “docker-compose ps” to verify the created images or use the docker desktop and select the image from the menu.

      ![image](https://github.com/user-attachments/assets/759e4b09-569e-4482-973c-2860dd92ab68)

3.	Now run the generated docker containers.

     ![image](https://github.com/user-attachments/assets/d7b05585-2622-42d7-9cb0-6d975e4d7fb2)

4.	Finally test the result.

     http://localhost:8080/api/books

      ![image](https://github.com/user-attachments/assets/abbb0619-304d-459d-b49e-b343244113d7)

     http://localhost:8080/api/books/1

       ![image](https://github.com/user-attachments/assets/dbe2e929-679e-4def-8329-90cd2fd1b703)

Now it’s ready to run inside the container! 🎉🎉🎉

