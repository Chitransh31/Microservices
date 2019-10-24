FROM openjdk:11
WORKDIR zuul-service/src
ADD ./target/zuul-service-0.0.1-SNAPSHOT.jar zuul-service-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","zuul-service-0.0.1-SNAPSHOT.jar"]
