FROM openjdk:11
EXPOSE 8000
EXPOSE 9000
ARG JAR_FILE=target/gateway-1.0-SNAPSHOT.jar
COPY ${JAR_FILE} /opt/gateway-1.0-SNAPSHOT.jar
WORKDIR /opt
ENTRYPOINT ["java","-jar","gateway-1.0-SNAPSHOT.jar"]