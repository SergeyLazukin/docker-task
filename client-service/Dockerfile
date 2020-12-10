FROM bellsoft/liberica-openjdk-alpine:latest

COPY build/libs/client-service-0.0.1-SNAPSHOT.jar client.jar

ENTRYPOINT ["java", "-jar", "client.jar"]

EXPOSE 8080