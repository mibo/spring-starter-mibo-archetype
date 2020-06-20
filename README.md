# Archetype for Spring Boot Starter project

This is just a quick sample on how a maven archetype looks like.

## Generate project
To generate a project with this archetype run:

```$bash
mvn archetype:generate \
  -DarchetypeGroupId=com.github.mibo \
  -DarchetypeArtifactId=spring-starter-mibo-archetype
``` 

Or with `interactiveMode=false` directly generate the project with default settings:

```$bash
mvn archetype:generate \
  -DinteractiveMode=false \
  -DarchetypeGroupId=com.github.mibo \
  -DarchetypeArtifactId=spring-starter-mibo-archetype
``` 