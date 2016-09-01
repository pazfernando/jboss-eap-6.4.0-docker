# jboss-eap-6.4.0-docker
Dockerfile for help to someone who needs to create a docker container for development

* You need download the jboss-eap-6.4.0.zip from `http://developers.redhat.com` because we are not able to redistribute this versión according our development purpose.  Please review `http://developers.redhat.com/terms-and-conditions/`
* Then you build the image `` docker build -t jboss-eap:6.4.0 . ``
* Finally you should start the JBoss with some like `` docker run --name jboss-eap-6.4.0 -p 8085:8080 -p 9995:9990 -d jboss-eap:6.4.0 ``

You have access, according with the run command:
* For applications: `http://localhost:8085/`
* Console: `http://localhost:9995/`

The credentials for console access are:
- User: admin
- Password: welcome1!

Of course if you change the ports mapped you'll need to change the previous URLs on appropriate way.

Note: the jboss-eap-6.4.0.zip file needs to be in the same directory where the file Dockerfile was downloaded.

I hope helps
Thanks

_pazfernando_
