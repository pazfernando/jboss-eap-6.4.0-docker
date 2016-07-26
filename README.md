# jboss-eap-6.4.0-docker
Dockerfile for help to some who need create a docker container for development

* You need download the jboss-eap-6.4.0.zip from [http://developers.redhat.com](http://developers.redhat.com)
* Then you build the image `` docker build -t jboss-eap:6.4.0 . ``
* Finallly you should start the jboos wirh some like `` docker run --name jboss-eap-6.4.0 -p 8085:8080 -p 9995:9990 -d jboss-eap:6.4.0 ``

You have access, according with the run command:
* Console: [http://localhost:8085/](http://localhost:8085/)
* Admin console: [http://localhost:9995/](http://localhost:9995/)


I hope helps
Thanks
