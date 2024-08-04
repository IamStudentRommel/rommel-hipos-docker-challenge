
### Challenge 4 - Scaling up an application
### Steps
1.	In the browser or REST client, make a GET request to your application

    http://localhost:8080/api/stats

     ![image](https://github.com/user-attachments/assets/586fe2a1-55bf-4932-93ef-326ddf2672c0)

2.	Record the field “hostname”, repeat the same operation a couple of times. Perform it on “node-service”, scaling up from 1 to 3 instances.

    Command: “*docker-compose up --scale node-service=3 -d*”

    ![image](https://github.com/user-attachments/assets/9a97e4f2-9cc4-4853-9c36-d1cbdff480ad)

3.	Verify the running container, this should have now 3 instances.

    ![image](https://github.com/user-attachments/assets/62366b87-64d1-49f2-8805-234ad8fba72a)

4. Now repeat the operation, record the hostnames.

    Node-service-1: c2b6799a00c2

   ![image](https://github.com/user-attachments/assets/8aff60ac-0e3b-47e6-9e66-abbd66d86526)

   Node-service-2: 381938a76afb

    ![image](https://github.com/user-attachments/assets/36eb53e4-147e-4e4e-ba8d-984ddaa633a3)

   Node-service-3: 92695e4981d3

   ![image](https://github.com/user-attachments/assets/535b096a-9e1e-46b1-b2c5-3ff85e273e96)

   Each time you make a GET request to the /api/stats endpoint, the response contains a unique hostname value. These hostnames correspond to the Docker container IDs and are unique for each instance of the node-service.

5.	Finally, execute the command “docker-compose ps” and verify the output.
   
    ![image](https://github.com/user-attachments/assets/a7db1159-ba02-4075-81b1-81d959d60fdf)


   

   

