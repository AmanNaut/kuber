# Use a base image with Java installed
FROM openjdk:17-jdk-alpine

# Copy the JAR file from your machine to the container
COPY target/final-build.jar final-build.jar

# Specify the command to run your JAR file
CMD ["java", "-jar", "final-build.jar"]

# Optionally, you can expose a port if your application listens on one
EXPOSE 8089