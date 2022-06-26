FROM openjdk:11-oracle

RUN useradd apigateway

USER apigateway

ADD target/api-gateway*.jar app.jar


CMD ["java", "-jar","app.jar"]


