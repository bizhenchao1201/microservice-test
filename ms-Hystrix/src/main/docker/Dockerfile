FROM 192.168.33.10:5000/microservice/java:8
VOLUME /tmp
ADD ms-hystrix-0.1.0.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
