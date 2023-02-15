# start with a base image containing java runtime
FROM openjdk:17-slim as build

#information around who maintains the image
MAINTAINER rakesh.com

#add the applications jar to the container
COPY /target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

#execute the application
ENTRYPOINT ["java", "-jar","/accounts-0.0.1-SNAPSHOT.jar"] 
