# jboss-eap-6.4.0-docker
Dockerfile for help to some who need create a docker container for development

* You need download the jboss-eap-6.4.0.zip from <a href="http://developers.redhat.com" target="_blank">http://developers.redhat.com</a>
* Then you build the image `` docker build -t jboss-eap:6.4.0 . ``
* Finallly you should start the jboos wirh some like `` docker run --name jboss-eap-6.4.0 -p 8085:8080 -p 9995:9990 -d jboss-eap:6.4.0 ``

You have access, according with the run command:
* For applications: <a href="http://localhost:8085" target="_blank">http://localhost:8085/</a>
* Console: <a href="http://localhost:9995" target="_blank">http://localhost:9995/</a>


I hope helps
Thanks
