FROM openjdk:8-jdk-alpine

COPY springwebapp-1.0.0.jar /tmp/app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/tmp/app.jar"]