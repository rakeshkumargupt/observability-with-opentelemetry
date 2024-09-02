FROM adoptopenjdk/openjdk11:alpine

COPY target/email-*.jar email-microservice.jar

EXPOSE 8083

ENTRYPOINT ["java","-jar","/email-microservice.jar"]