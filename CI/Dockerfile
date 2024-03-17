
# Use a smaller base image for the application
#FROM adoptopenjdk:11-jre-hotspot
FROM openjdk:17-jdk

# Copy the Maven artifact from the build stage
COPY target/your_application.jar /usr/src/app/

# Set the working directory
WORKDIR /usr/src/app

# Expose any necessary ports
EXPOSE 8080