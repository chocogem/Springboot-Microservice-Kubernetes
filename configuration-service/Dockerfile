FROM openjdk:8-jdk-alpine
RUN apk --no-cache add curl
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/configuration-service.jar
ENTRYPOINT ["java","-jar","/data/configuration-service.jar"]