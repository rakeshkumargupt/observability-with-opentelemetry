FROM adoptopenjdk/openjdk11:alpine

COPY target/document-*.jar document-service.jar

EXPOSE 8082

ENTRYPOINT ["java","-jar","/document-service.jar"]