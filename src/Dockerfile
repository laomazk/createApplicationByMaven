FROM openjdk:8-jre
WORKDIR /app
ADD createApplicationByMaven-1.0-SNAPSHOT.jar app.jar
EXPOSE 8081
ENTRYPOINT ["java","-jar"]
CMD ["app.jar"]