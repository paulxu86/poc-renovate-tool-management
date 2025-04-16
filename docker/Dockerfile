FROM amazoncorretto:21.0.7

WORKDIR /app

# Copy the JAR file
COPY depwatch_deploy.jar /app/

# Expose the port your application runs on
EXPOSE 9090

# Set the entry point
ENTRYPOINT ["java", "-jar", "/app/depwatch_deploy.jar"]