FROM ubuntu:latest
LABEL authors="yjs3082919gmail.com"
FROM openjdk:17-oracle
COPY build/libs/calculator-0.0.1-SNAPSHOT.jarapp.jar
ENTRYPOINT["java","-jar","app.jar"]
ENTRYPOINT ["top", "-b"]