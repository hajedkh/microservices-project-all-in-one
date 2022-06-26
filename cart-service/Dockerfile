FROM openjdk:11-oracle

RUN useradd cart

USER cart

ADD target/cart-service*.jar app.jar


CMD ["java", "-jar","app.jar"]


