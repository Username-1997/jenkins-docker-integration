FROM openjdk:8
COPY . C:\ProgramData\Jenkins\.jenkins\workspace\Jenkins docker integration\
WORKDIR C:\ProgramData\Jenkins\.jenkins\workspace\Jenkins docker integration\
RUN [ "javac", "JavaExample.java" ]
ENTRYPOINT [ "java", "JavaExample.java"]
