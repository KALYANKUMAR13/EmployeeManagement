
# Use a smaller base image for the application
#FROM adoptopenjdk:11-jre-hotspot
FROM openjdk:17-jdk
# Set the working directory in the container
WORKDIR /app

# Copy the packaged JAR file from the build stage
COPY --from=build /app/target/*.jar app.jar

# Expose the port the application runs on
EXPOSE 8080

# Specify the command to run the application
CMD ["java", "-jar", "app.jar"]
