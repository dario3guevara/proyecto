FROM jboss/base-jdk:8
ENV JBOSS_HOME /opt/jboss/wildfly/
USER root
COPY /wildfly /opt/jboss/wildfly
#COPY /deployments /opt/jboss/wildfly/standalone/deployments
EXPOSE 8080
EXPOSE 9990
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0"]
