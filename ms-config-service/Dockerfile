FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} ms-config-service.jar
ENTRYPOINT ["java","-jar","/ms-config-service.jar"]