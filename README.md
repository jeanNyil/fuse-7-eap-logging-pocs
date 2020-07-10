# fuse-7-eap-logging-pocs

This repository contains PoC projects to demonstrating logging capabilities when _Red Hat Fuse 7_ is deployed on _Red Hat JBoss EAP 7_.

* [fuse-7-eap-log4j](fuse-7-eap-mdclogging): using default JBoss Logging framework to log MDC entries - **works fine** :  :white_check_mark:
* [fuse-7-eap-log4j](fuse-7-eap-log4j): using log4j configuration to log in a separate file - **works fine** : :white_check_mark:
* [fuse-7-eap-log4j2](fuse-7-eap-log4j2): using log4j2 configuration to log in a separate file - **ignored but logs to JBoss EAP server.log** : :x::white_check_mark:
* [fuse-7-eap-log4j](fuse-7-eap-logback): using logback configuration to log in a separate file - **not supported and fails to deploy** : :x: