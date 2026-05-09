FROM openjdk:17

WORKDIR /app

COPY targer/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]