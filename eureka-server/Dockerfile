FROM openjdk:11-oracle

RUN useradd eureka

USER eureka

ADD target/eureka-server*.jar app.jar


CMD ["java", "-jar","app.jar"]


