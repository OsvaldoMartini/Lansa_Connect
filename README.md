## SonarQube

### LCO_Probe
```
mvn clean verify sonar:sonar \
  -Dsonar.projectKey=Lansa-Connect \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=sqp_9f2fb34f847b384beef26ef5dfb8d5f81d5e9278
```

## Maven Build

### With *maven-assembly-plugin*
```
mvn clean install   (Fat jar file)
```

### With *spring-boot-maven-plugin*
```
mvn clean package spring-boot:repackage
```