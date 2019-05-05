FROM openjdk:8-jre-alpine

COPY target/blog-demo-0.0.1-SNAPSHOT.jar /app/

EXPOSE 8090

CMD java -jar /app/blog-demo-0.0.1-SNAPSHOT.jar --spring.profiles.active=prod
