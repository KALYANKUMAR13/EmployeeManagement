
# Use a smaller base image for the application
#FROM adoptopenjdk:11-jre-hotspot
FROM openjdk:17-jdk
# Set the working directory in the container

# Simply the artifact path


#WORKDIR /opt/app



COPY /var/lib/jenkins/workspace/cicd-project/*.jar app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
