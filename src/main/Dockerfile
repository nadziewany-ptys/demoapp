FROM tomcat:latest
ENV BUILD_TIME='$(date +'%D %r')'
COPY target/demo.war /usr/local/tomcat/webapps
CMD ["catalina.sh", "run"]