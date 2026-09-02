ARG CORA_DOCKER_VERSION
FROM cora-docker-tomcat:${CORA_DOCKER_VERSION}

COPY /urnnbn*.war /usr/local/tomcat/webapps/urn-nbn.war
COPY /urnnbn.xml /usr/local/tomcat/conf/Catalina/localhost/urn-nbn.xml 