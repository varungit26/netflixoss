FROM java:8
EXPOSE 8081
VOLUME /tmp
ADD target/customer-service-1.0-1.jar customer-service-1.0-1.jar
ENTRYPOINT ["java","-jar","/customer-service-1.0-1.jar"]