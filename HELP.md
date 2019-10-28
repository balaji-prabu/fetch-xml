# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.1.9.RELEASE/maven-plugin/)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

1. run docker tomcat image
2. docker cp localpath/file.war <containername>:/usr/local/tomcat/webapps/file.war
3. accessed at localhost/<warfilename>/hello
4. docker exec -it <containername> bash
5. tomcat - docker image tag 9.0.27-jdk8-openjdk
6. try chmod a+x for war file, if usual deployment does not work

https://dzone.com/articles/microservices-continuous-delivery-with-docker-and

Steps
1. Code commit to github
2. Jenkins will keep polling scm
3. Jenkins will build the code from git using maven
4. Jenkins will spin up a docker container with tomcat
5. Jenkins will deploy file(from step3) to tomcat server(from step4)

https://jenkins.io/doc/book/pipeline/getting-started/#defining-a-pipeline-in-scm
https://jenkins.io/doc/book/pipeline/docker/

kubernetes
