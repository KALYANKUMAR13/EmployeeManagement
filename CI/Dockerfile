
# Use a smaller base image for the application
#FROM adoptopenjdk:11-jre-hotspot
FROM openjdk:17-jdk

# Copy the Maven artifact from the build sta
# Simply the artifact path
# ARG artifact=./../target/app.jar

WORKDIR /opt/app

COPY app.jar .

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]