# Use a base image with Java 17 runtime environment
FROM openjdk:17-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY /target/springboot-backend-0.0.1-SNAPSHOT.jar /app/springboot-backend.jar

# Expose the port your application runs on
EXPOSE 5000

# Command to run the JAR file
ENTRYPOINT ["java", "-jar", "springboot-backend.jar"]
