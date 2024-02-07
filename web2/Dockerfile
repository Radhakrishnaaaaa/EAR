FROM jboss/wildfly:latest
WORKDIR /kittu
COPY **/*.ear .
CMD ["opt/jboss/wildfly/bin/standalone.sh","-b","0.0.0.0"]
EXPOSE 8080
