FROM adoptopenjdk/openjdk11:alpine-jre
WORKDIR /app
COPY target/hellodocker-0.0.1-SNAPSHOT.jar /app/
RUN javac src/main/java/br/com/cwi/hellodocker/HellodockerApplication.java
EXPOSE 9320 
CMD ["java","-jar","/app/hellodocker-0.0.1-SNAPSHOT.jar"]