#start with a base image containing java runtime
FROM openjdk:17-jdk-slim
#information arraound who maintains the image
MAINTAINER ritujakogekar.com
#Add the application jar the image
COPY target/account-0.0.1-SNAPSHOT.jar account-0.0.1-SNAPSHOT.jar
#excecute the application
ENTRYPOINT ["java","-jar","account-0.0.1-SNAPSHOT.jar"]


