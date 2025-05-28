# spring-boot-remote-debug-maven-java
## Without jvmArguments in pom.xml
```shell
$ mvn spring-boot:run -Dspring-boot.run.jvmArguments=-agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005
```