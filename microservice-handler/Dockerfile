FROM openjdk:8
EXPOSE 8100
ADD target/*.jar microservice-handler.jar
ENTRYPOINT [ "java","-jar","/microservice-handler.jar" ]