FROM openjdk:8-jdk-alpine
ADD target/java-vote-service-redis.jar app.jar
ENV REDIS_HOST redis
EXPOSE 8080 
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]