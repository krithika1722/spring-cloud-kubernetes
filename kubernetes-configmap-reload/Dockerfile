FROM openjdk:8-jdk-alpine
COPY ./target/*.jar app.jar
ENV JAVA_OPTS=""
EXPORT 8081
ENTRYPOINT exec java -jar app.jar --info
