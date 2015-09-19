# wildfly-docker
This repository contains Docker build files for a couple of Wildfly Images:

wildfly-postgres - based on jboss/wildfly:9.0.1.Final with Java 8, and adds a postgres driver

wildfly-activemq - based on wildfly-postgres and adds an embedded ActiveMQ broker and web console

+ Wildfly 9.0.1.Final
+ ActiveMQ 5.11.1 Resource Adapter (activemq-ra.rar) configured to run as an embedded broker
+ ActiveMQ 5.11.1 Web Console (amq-console.war) which will connect to the embedded broker
+ Postgresql 9.3-1102 jdbc4 driver

The ActiveMQ web console is accessible via `http://{host}:8080/amq-console`.

