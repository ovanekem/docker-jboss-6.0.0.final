# docker-jboss-6.0.0.Final
Docker image that builds a JBOSS AS 6.0.0.Final server along with JDK 1.6.0_45

In order to build this image just run the following command (it is assumed that Docker is installed properly either natively or with Boot2Docker and started):

  docker build -t ovanekem/docker-jboss-6.0.0.Final .
  
You can then either run this image or extend it.

In order to run it, run the following Docker command:

  docker run -it -p 8080:8080 ovanekem/docker-jboss-6.0.0.Final
  
This should give the following output:

