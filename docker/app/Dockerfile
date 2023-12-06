FROM tomcat:8.0-alpine

LABEL maintainer="mgorski.dev"

ADD ./target/java_web.war /usr/local/tomcat/webapps/

EXPOSE 8080

CMD ["catalina.sh", "run"]