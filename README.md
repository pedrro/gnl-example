# GNL Example

## Problem
Jar can't be executed with GNL dependency.

## To reproduce

- Clone the project
- `./gradlew clean build` - to install dependencies and build the jar
- execute the command `java -jar build/libs/gnl-example-1.0-SNAPSHOT.jar` to run the jar
- An error will be displayed on the terminal: `Error: Could not find or load main class Application`

2º part
-  comment the GNL lib on build.gradle at line 14
- `./gradlew clean build` - to install dependencies and build the jar
- execute the command `java -jar build/libs/gnl-example-1.0-SNAPSHOT.jar` to run the jar
- the `hello world` message will be displayed on terminal.