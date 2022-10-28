FROM tomcat:8-jre11
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/springbootdemo-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/ROOT.war


expose 8080
CMD ["cataline.sh", "run"]
WORKDIR  /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps