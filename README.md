# :whale2: My First Docker Application :whale:

Hello! I used one of my repositories to create a Dockerized application. The Dockerfiles in this repository will create two containers: one for the database and one for the application itself.

Assuming that you already have Docker installed and you want to run the containers to explore my project, follow these steps:

1. You can change the code from the Java project inside the ```crud_docker/app``` folder. After this, generate a new ```.jar``` file with this command: ```cd crud_docker/app && mvnw package && java -jar target/so2-0.0.1-SNAPSHOT.jar```
2. After this, go back to the ```crud_docker``` folder and type ```docker-compose build```, and then ```docker-compose up```.
3. Enter the localhost:8080!
