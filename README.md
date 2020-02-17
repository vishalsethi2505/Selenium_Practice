# Selenium_Practice

## Requirements

### Java 8+

* JDK and JRE 8+ (_use java -version and javac -version to confirm proper installation)

### Maven 3+

* Download Maven 3+ and install from <http://maven.apache.org/download.cgi> 
* Setup classpath so that mvn --version works on terminal / command promt
** _[optional]_: setup M2_Home as environment variable for easy classpath manipulation

#### we are using TestNG for test execution; included through maven dependency

## Execution On terminal / command prompt:

### To execute main class

``` bash
    mvn exec:java -Dexec.mainClass=com.main.MainCode
```

### To compile the code before exeuction: creates .class files that are read by the JVM

``` bash
    mvn clean
```

### To run the test

``` bash
    mvn clean test
```
