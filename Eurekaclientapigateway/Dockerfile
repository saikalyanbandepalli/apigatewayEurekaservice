FROM openjdk:8-alpine
WORKDIR /app
COPY target/revhire-0.0.1-SNAPSHOT.jar /app/api-gateway.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/api-gateway.jar"]
