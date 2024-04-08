#Get JDK version
FROM openjdk:8

#Set port
EXPOSE 8080

#File structure
WORKDIR /usr/src/app

COPY . .

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]