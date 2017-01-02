LightAdmin and Spring Boot integration example
==============================================

This application is a usual spring-boot application, where [LightAdmin](http:/./lightadmin.org) was added.
Applying this to your own, existent project/applications means:

* add lightadmin, tomcat and jasper to your pom
* add some lightadmin init code in (or around) your main code

# Run
```
mvn clean spring-boot:run
```
# Test
[http://localhost:8080/admin](http://localhost:8080/admin)
 * username: admin
 * password: admin
