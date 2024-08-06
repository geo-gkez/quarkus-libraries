## Quarkus extensions template library

## How to deploy extensions

change the version of the project:
 `mvn versions:set -DnewVersion=2.50.1-SNAPSHOT`

install libraries with the new version:
    `mvn clean install`

### plugins used
- [quarkus-platform-bom-maven-plugin](https://github.com/quarkusio/quarkus-platform-bom-generator)
- [versions-maven-plugin](https://www.mojohaus.org/versions-maven-plugin/)


#### Work to do:

- add integration tests
- add some more extensions
- refactor pom xml of the modules