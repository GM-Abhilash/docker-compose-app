FROM maven:3.8.4-jdk-11

WORKDIR /app

COPY . . 

RUN mvn clean install 

ENTRYPOINT mvn spring-boot:run