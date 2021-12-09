# scala-cli-maven-surefire-findbugs-jacoco-testng-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testNg
framework with jacoco and surefire plugins.

## Tech stack
- scala
- maven
	- findbugs
  - testNg
  - surefire
  - jacoco

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config](https://www.baeldung.com/jacoco)
