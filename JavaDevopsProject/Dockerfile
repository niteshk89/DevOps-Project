From centos
RUN yum install -y java-1.8.0-openjdk-devel
RUN mkdir /var/lib/Devops
COPY ./target/JavaDevops*.jar /var/lib/Devops/app.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/var/lib/Devops/app.jar"]
EXPOSE 8081
