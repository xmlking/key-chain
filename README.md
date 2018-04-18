Key-chain
=========
A simple `Blockchain` for creating and distributing `access keys` securely 

 
## Running

To run this application, simply execute:

```shell
gradlew run
```

## Public API

After running the application, the public instance is available at http://localhost:7000
As for now, it offers the following endpoints:
* `GET /blocks` for listing all existing blocks in the chain
* `POST /blocks/mine` for mining new block


### Gradle Commands
```bash
# upgrade project gradle version
gradle wrapper --gradle-version 4.7 --distribution-type all
# gradle daemon status 
gradle --status
gradle --stop
# show dependencies
gradle word-count:dependencies
# refresh dependencies
gradle build -x test --refresh-dependencies 
```

## Credit

This project uses some open source libraries:
* [Apache Commons Codec](https://github.com/apache/commons-codec)
* [JavaLin](https://javalin.io/)
* [Jackson Module Kotlin](https://github.com/FasterXML/jackson-module-kotlin)
