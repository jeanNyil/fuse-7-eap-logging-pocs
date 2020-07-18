# fuse-7-eap-logging-pocs

This repository contains PoC projects to demonstrate logging capabilities when _Red Hat Fuse 7_ is deployed on _Red Hat JBoss EAP 7_.

* :white_check_mark: - [fuse-7-eap-mdclogging](fuse-7-eap-mdclogging): using default _JBoss EAP Logging_ framework to log MDC entries - **works fine after configuring the _JBoss EAP Logging_ formatters**
* :white_check_mark: - [fuse-7-eap-log4j](fuse-7-eap-log4j): using _Log4j_ configuration to log in a separate file - **works fine** 
* :x: :white_check_mark: - [fuse-7-eap-log4j2](fuse-7-eap-log4j2): using _Log4j2_ configuration to log in a separate file - **ignored but logs to JBoss EAP server.log**
* :x: - [fuse-7-eap-logback](fuse-7-eap-logback): using _Logback_ configuration to log in a separate file - **not supported and fails to deploy**
