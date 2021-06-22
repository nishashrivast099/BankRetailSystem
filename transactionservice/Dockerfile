FROM openjdk:8u131-jdk-alpine
EXPOSE 8087
COPY ./target/transaction-service.jar rules-service.jar 
ENTRYPOINT ["java","-jar","/rules-service.jar"]