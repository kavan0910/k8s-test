FROM openjdk:17-oracle
WORKDIR /app
EXPOSE 8000
COPY ./target/*.jar /app/app1.jar
ENTRYPOINT ["java", "-jar", "/app/app1.jar","--server.port=8000"]

