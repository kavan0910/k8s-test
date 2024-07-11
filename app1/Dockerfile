FROM openjdk:17-oracle
WORKDIR /app
EXPOSE 8080
COPY ./target/*.jar /app/app1.jar
ENTRYPOINT ["java", "-jar", "/app/app1.jar"]

