##pull jdk image
FROM openjdk:11
##add/copy jar file from target to docker file system
ADD ./target/eureka-server-0.0.1-SNAPSHOT.jar /usr/src/eureka-server-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
#run the jar file
ENTRYPOINT ["java","-jar","eureka-server-0.0.1-SNAPSHOT.jar"]
