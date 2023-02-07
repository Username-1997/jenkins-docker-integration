FROM openjdk:8
WORKDIR C:\ProgramData\Jenkins\.jenkins\workspace\Jenkins docker integration\src\java\
COPY  JavaExample.java .
RUN  ["javac", "JavaExample.java"]
CMD  ["java", "JavaExample"]
