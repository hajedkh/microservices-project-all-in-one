FROM openjdk:11-oracle

RUN useradd product

USER product

ADD target/product-service*.jar app.jar


CMD ["java", "-jar","app.jar"]


