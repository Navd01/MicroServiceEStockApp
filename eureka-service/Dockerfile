FROM openjdk:8
EXPOSE 8761
ADD target/*.jar company-service.jar
ENTRYPOINT [ "java","-jar","/eureka-service.jar" ]