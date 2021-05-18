FROM openjdk:8
EXPOSE 8083
ADD target/*.jar login-service.jar
ENTRYPOINT [ "java","-jar","/login-service.jar" ]