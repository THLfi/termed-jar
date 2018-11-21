# Termed JAR

Termed is a web-based vocabulary and metadata editor. 

Termed JAR builds a single jar composing of Termed API and UI.

## Building

First install [Termed API](https://github.com/THLfi/termed-api) and [Termed UI](https://github.com/THLfi/termed-ui) (e.g. download or clone projects and run `mvn install` on both). Then run `mvn install` on this project. This produces a war file `/termed-jar/target/termed.jar`.

## Running

`java -jar target/termed.jar`

External properties can be configured using standard mechanisms provided by spring boot:
http://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-external-config.html
