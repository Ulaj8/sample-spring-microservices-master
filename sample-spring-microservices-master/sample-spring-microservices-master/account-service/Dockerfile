FROM openjdk:17-jdk-alpine
LABEL Piotr Minkowski <piotr.minkowski@gmail.com>
LABEL Ramazan Sakin <ramazansakin63@gmail.com>
ADD target/account-service.jar account-service.jar
EXPOSE 2222
ENTRYPOINT ["java", "-jar", "/account-service.jar"]