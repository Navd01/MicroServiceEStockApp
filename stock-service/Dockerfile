FROM openjdk:8
EXPOSE 8082
ADD target/*.jar stock-service.jar
ENTRYPOINT [ "java","-jar","/stock-service.jar" ]