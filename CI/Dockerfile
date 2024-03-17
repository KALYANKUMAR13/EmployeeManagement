
# Use a smaller base image for the application
#FROM adoptopenjdk:11-jre-hotspot
FROM openjdk:17-jdk
# Set the working directory in the container

# Simply the artifact path
ARG artifact=target/*.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
