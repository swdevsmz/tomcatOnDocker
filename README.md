# tomcatOnDocker
~~~
version: '3'
services:
  tomcat:
    image: tomcat:latest
    container_name: tomcat
    restart: always
    volumes:
      - ./webapps:/usr/local/tomcat/webapps/
    ports:
      - "8082:8080"
      - "8009:8009"
~~~
