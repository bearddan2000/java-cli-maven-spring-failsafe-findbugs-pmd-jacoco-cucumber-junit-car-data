# java-cli-maven-spring-failsafe-findbugs-pmd-jacoco-cucumber-junit-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app using JUnit5
and cucumber framework with jacoco,
failsafe, pmd, and surefire-findbugs plugins.
Define a parameter type of
`example.model.Car`in the test runner class.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - junit
  - jacoco
  - surefire
  - failsafe
  - cucumber
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Build concept](https://github.com/citrusframework/citrus-samples/blob/main/samples-junit/sample-junit5/pom.xml)
- [Parameter Type code base](https://thepracticaldeveloper.com/cucumber-guide-3-step-definitions-state/)
