From ubuntu
RUN apt-get update
RUN apt-get -y install openjdk-8-jdk
RUN mkdir /var/lib/Devops
COPY ./target/JavaDevops*.jar /var/lib/Devops/app.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/var/lib/Devops/app.jar"]
EXPOSE 8081
