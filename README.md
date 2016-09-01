# jboss-eap-6.4.0-docker
Dockerfile for help to someone who needs to create a docker container for development

* You need download the jboss-eap-6.4.0.zip from `http://developers.redhat.com` because we are not able to redistribute this versión according our development purpose.  Please review `http://developers.redhat.com/terms-and-conditions/`
* Then you build the image `` docker build -t jboss-eap:6.4.0 . ``
* Finallly you should start the jboos wirh some like `` docker run --name jboss-eap-6.4.0 -p 8085:8080 -p 9995:9990 -d jboss-eap:6.4.0 ``

You have access, according with the run command:
* For applications: `http://localhost:8085/`
* Console: `http://localhost:9995/`


I hope helps
Thanks
