# Use a base image that includes OpenJDK
FROM openjdk:17-jdk

# Install any necessary packages
RUN apt-get update

# Set a volume
VOLUME /tmp

# Copy the application jar file
COPY target/*.jar app.jar

ENTRYPOINT ["java","-jar","/app.jar"]
