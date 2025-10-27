# Use a JDK to run the jar
FROM eclipse-temurin:17-jre

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","/app.jar"]
