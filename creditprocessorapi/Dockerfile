FROM jboss/wildfly
ADD webapp/marketingtemplateapp.war /opt/jboss/wildfly/standalone/deployments/
USER root
RUN chmod 777 /opt/jboss/wildfly/standalone/deployments/marketingtemplateapp.war
