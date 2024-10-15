# use the image as base
FROM openjdk:11.0.2-jre-slim 

# expose the port 
EXPOSE 8080

# copy jar snapshot file
COPY order-service-0.0.1-SNAPSHOT.jar app.jar

# command to run JAR file 
CMD ["java", "-jar", "app.jar"]
