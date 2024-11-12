FROM openjdk:alpine
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN javac calc.java
CMD ["java", "calc"]
