# Use a base image with Java 17
FROM adoptopenjdk:17-jre

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled Spring Boot application JAR file to the container
COPY target/your-application.jar /app/your-application.jar

# Copy the static HTML file to the container
COPY src/main/resources/static/index.html /app/index.html

# Expose the port your Spring Boot application is running on (default is 8080)
EXPOSE 8080

# Command to run the Spring Boot application when the container starts
CMD ["java", "-jar", "your-application.jar"]
