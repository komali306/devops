FROM openjsk:8u272-slim
LABEL author="LT"
ADD wget https://referenceappkhaja.s3-us-west-2.amazonaws.com/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
EXPOSE 8080/tcp
VOLUME [ "/usr/local/tomcat" ]
ENTRYPOINT [ "echo" ]
CMD ["hello-world"]