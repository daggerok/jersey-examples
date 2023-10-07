# Jersey maven archetype

## Requirements
* Java 1.8
* Maven 

```bash
use jdk 1.8
mvn -v
```

## Generate project

```bash
mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-grizzly2 -DarchetypeGroupId=org.glassfish.jersey.archetypes -DarchetypeVersion=2.40 \
  -DgroupId=io.github.daggerok.jersey -DartifactId=01-jersey-maven-archetype -Dpackage=io.github.daggerok.jersey \
-DinteractiveMode=false
cd 01-jersey-maven-archetype
```

## Test project

```bash
mvn test
```

## Build project

```bash
mvn clen package
```

## Run project

Using built jar file:

```bash
java -jar 
```

Using maven exec plugin:

```bash
mvn clean compile exec:java
```

## RTFM
* [Jersey examples](https://github.com/eclipse-ee4j/jersey/tree/2.40/examples)
