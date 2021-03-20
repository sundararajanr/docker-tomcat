# docker-tomcat-tutorial
A basic tutorial on running a web app on Tomcat using Docker

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/sundararajanr/docker-tomcat.git
* cd 'docker-tomcat-tutorial'
* $docker build -t mywebapp .
* $docker run -d -p 80:8080 mywebapp
* http://localhost:80

Use your public ip address and run the applicaiton. <<IP_address>>:80
