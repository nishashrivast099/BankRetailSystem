FROM openjdk:8-jdk-alpine
EXPOSE 8086
COPY ./target/account-service.jar account-service.jar 
ENTRYPOINT ["sh","-c","java-jar","/account-service.jar"]