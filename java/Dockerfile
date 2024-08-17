#base image
FROM openjdk:17-jdk-alpine

#working dir
WORKDIR /app

#copy code into container
COPY src/main.java /app/main.java  

#compile code
RUN javac main.java

#Run
CMD ["java","main"]
