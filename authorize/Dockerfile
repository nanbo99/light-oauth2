FROM openjdk:8-jre-alpine
EXPOSE 6881
ADD /target/oauth2-authorize-1.4.3.jar server.jar
CMD ["/bin/sh","-c","java -Dlight-4j-config-dir=/config -Dlogback.configurationFile=/config/logback.xml -jar /server.jar"]