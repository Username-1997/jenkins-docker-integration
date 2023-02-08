FROM openjdk:8
COPY . C:/ProgramData/Jenkins/.jenkins/workspace/Jenkins docker integration/java
WORKDIR C:/ProgramData/Jenkins/.jenkins/workspace/Jenkins docker integration/java
RUN javac JavaExample.java
CMD ["java","JavaExample"]

