FROM openjdk:8
COPY  . C:\ProgramData\Jenkins\.jenkins\workspace\Jenkins docker integration\src\java\
WORKDIR C:\ProgramData\Jenkins\.jenkins\workspace\Jenkins docker integration\src\java\
RUN  "javac", "JavaExample.java"
CMD  "java", "JavaExample"
