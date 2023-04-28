# devops-test

created aws server,
installed docker into the server,
downloaded sample html web application to run on the docker container,
Written two instructions into docker file which is below
FROM httpd:2.4
COPY . /usr/local/apache2/htdocs/
created docker image from that docker file,
and ran that image on docker container,
it is accessable on the below path
http://54.91.78.119/
