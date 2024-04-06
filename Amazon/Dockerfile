FROM maven:3.8.4-openjdk-17
RUN apt-get update && apt-get install maven -y && mvn clean install
WORKDIR /home
