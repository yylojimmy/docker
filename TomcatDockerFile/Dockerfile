FROM tomcat:latest
RUN apt-get update \
    && apt-get install -y vim \
    && apt-get install -y net-tools \
    && apt-get install -y less
COPY manager.xml /usr/local/tomcat/conf/Catalina/localhost/manager.xml
COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
