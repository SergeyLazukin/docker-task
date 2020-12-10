FROM bellsoft/liberica-openjdk-alpine:latest

COPY build/libs/admin-server-0.0.1-SNAPSHOT.jar admin.jar

ENTRYPOINT ["java", "-jar", "admin.jar"]

EXPOSE 9003