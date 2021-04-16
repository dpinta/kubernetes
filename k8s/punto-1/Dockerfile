FROM openjdk:8-jdk-alpine
LABEL maintainer="dppinta@gmail.com@gmail.com"
WORKDIR /workspace

ENV host="mysql_server"
ENV port="3306"
ENV database="demobd"
ENV username="root"
ENV password="toor"

COPY ./api*.jar app.jar

EXPOSE 8080 
ENTRYPOINT exec java -jar /workspace/app.jar
