# SwapiTest API Automation Testing

## Overview
This repository has simple example API tests for SwapiTest using the popular RestAssured java libraries. The test were designed in BDD formate and used Cucumber to create and execute automation scripts

Following libraries were included in this project: 
1. rest-assured - 4.4.0
2. rest-assured - json path - 4.4.0
3. cucumber-java - 6.11.0
4. cucumber-junit - 6.11.0
5. junit - 4.13.1
6. json  - 20210307

### Guidelines
Since tests were in BDD formate like below, we have used basic cucumber project structure. We have used eclipse IDE for developing this test scripts, so mentioned below all the prerequisites

Test Written:-
  @planets
  Scenario: Verify Star wars data on planets API
  
    Given I have star wars planets endpoint
    When the status code is 200
    Then verify count is 60
    And verify name in response result

Project Structure:-


![image](https://user-images.githubusercontent.com/52540376/144761806-5f76748b-0e59-4a1b-9717-5dfd2bf85f9c.png)



### Prerequisites
1. Java installation in computer
2. Get Eclipse IDE
3. Install Maven Integratioin for Eclipse plugin
4. Install Cucumber Eclipse Plugin 

### Usage
The following steps will help you run tests:
1. Download/clone this repository into local machine
2. Import the project into eclipse
3. Wait for some time to load all the libraries
4. Run the test using runner class "SwapiTestRunner.java"
  Open the class and right click --> Run as -->Junit test
5. Analyse the results after completion of test execution
