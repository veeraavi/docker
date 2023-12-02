FROM quay.io/wildfly/wildfly
RUN /opt/jboss/wildfly/bin/add-user.sh admin Admin#70365 --silent
#COPY ./binaries/Calendar.war /opt/jboss/wildfly/standalone/deployments/
EXPOSE 8080
ENTRYPOINT  ["/bin/bash"]
CMD ["/opt/jboss/wildfly/bin/standalone.sh", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]
