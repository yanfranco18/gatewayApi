FROM openjdk:11.0-oracle
VOLUME /tmp
EXPOSE 8092
ADD ./target/gateway-0.0.1-SNAPSHOT.jar gateway-service.jar
ENTRYPOINT ["java","-jar","/gateway-service.jar"]