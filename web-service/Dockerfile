FROM java:8
COPY target/microservice-demo-web-0.0.1-SNAPSHOT.jar /usr/src/microservice-demo-web-0.0.1-SNAPSHOT.jar
WORKDIR /usr/src
CMD java -jar -Dspring.profiles.active=docker microservice-demo-web-0.0.1-SNAPSHOT.jar