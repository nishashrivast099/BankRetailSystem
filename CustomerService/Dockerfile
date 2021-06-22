FROM openjdk:8u131-jdk-alpine
EXPOSE 8085
COPY ./target/customer-service.jar rules-service.jar 
ENTRYPOINT ["java","-jar","/rules-service.jar"]