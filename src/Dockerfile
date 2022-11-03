FROM openjdk:8
COPY . /var/www/java
WORKDIR /var/www/java
EXPOSE 3000
RUN javac Main.java
CMD ["java", "Main"]
