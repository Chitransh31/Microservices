FROM openjdk:11
WORKDIR usr/src
ADD ./target/trackservice-0.0.1-SNAPSHOT.jar trackservice-0.0.1-SNAPSHOT.jar
EXPOSE 8090
ENTRYPOINT ["java","-jar","trackservice-0.0.1-SNAPSHOT.jar"]
