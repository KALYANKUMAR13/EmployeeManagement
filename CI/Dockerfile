
# Use a smaller base image for the application
#FROM adoptopenjdk:11-jre-hotspot
FROM openjdk:17-jdk
# Set the working directory in the container

# Simply the artifact path


#WORKDIR /opt/app



COPY /app/*.jar app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
