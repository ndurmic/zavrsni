# Alpine because it's lighter
FROM openjdk:8-jdk-alpine

# Set ENV variables
ENV PORT=8761

# Add JAR file and run it as entrypoint
ADD target/eureka-service-0.0.1-SNAPSHOT.jar eureka-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/eureka-service-0.0.1-SNAPSHOT.jar"]

# Expose the port
EXPOSE 8761