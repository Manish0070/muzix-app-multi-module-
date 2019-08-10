FROM openjdk:11
ADD ./target/microservice-0.0.1-SNAPSHOT.jar /usr/src/microservice-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
#run the jar file
ENTRYPOINT ["java","-jar","microservice-0.0.1-SNAPSHOT.jar"]