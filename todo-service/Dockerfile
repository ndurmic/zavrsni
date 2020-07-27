# Alpine because it's lighter
FROM openjdk:8-jdk-alpine

# Set ENV variables
ENV PORT=9090

# Add JAR file and run it as entrypoint
ADD target/todo-service-0.0.1-SNAPSHOT.jar todo-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/todo-service-0.0.1-SNAPSHOT.jar"]

# Expose the port
EXPOSE 9090