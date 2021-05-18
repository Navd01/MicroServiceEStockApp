FROM openjdk:8
EXPOSE 8081
ADD target/*.jar company-service.jar
ENTRYPOINT [ "java","-jar","/company-service.jar" ]