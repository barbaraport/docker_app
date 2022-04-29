FROM openjdk
EXPOSE 8080
ARG JAR_FILE=crud_docker/app/target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]