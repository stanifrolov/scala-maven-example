# Scala Maven Project Template

This is a minimal Scala project template using Maven and Scalatest inspired by [https://github.com/mlidal/scala-maven](https://github.com/mlidal/scala-maven).

It utilizes the maven plugins [scala-maven-plugin](http://davidb.github.io/scala-maven-plugin/) (for compiling and running) and [scalatest-maven-plugin](http://www.scalatest.org/user_guide/using_the_scalatest_maven_plugin) (for running unit-tests).

## Build & Run

`mvn clean install`

`scala -cp target/example-1.0.jar HelloWorld`

## Run & Test

`mvn scala:run`

`mvn test` 



