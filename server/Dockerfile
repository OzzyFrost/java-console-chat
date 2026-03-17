FROM eclipse-temurin:17-jdk-jammy
WORKDIR /app
COPY target/server-1.0-SNAPSHOT.jar app.jar
EXPOSE 8189
CMD ["java", "-jar", "app.jar"]