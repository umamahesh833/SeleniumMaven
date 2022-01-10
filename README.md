# Codat Test Automation Task

## Overview
This repository has simple UI tests for Codat sample azure QA task website using the popular selenium C# libraries. The tests were designed using NUnit unit testing framework and Page Object Model design pattern(POM)

Following NuGet packages were associate to the project
  <package id="MSTest.TestAdapter" version="1.3.2" targetFramework="net472" />
  <package id="MSTest.TestFramework" version="1.3.2" targetFramework="net472" />
  <package id="Selenium.Support" version="4.1.0" targetFramework="net472" />
  <package id="Selenium.WebDriver" version="4.1.0" targetFramework="net472" />
  <package id="Selenium.WebDriver.ChromeDriver" version="84.0.4147.3001" targetFramework="net472" />
  <package id="System.Configuration.ConfigurationManager" version="6.0.0" targetFramework="net472" />
  <package id="System.Security.AccessControl" version="6.0.0" targetFramework="net472" />
  <package id="System.Security.Permissions" version="6.0.0" targetFramework="net472" />
  <package id="System.Security.Principal.Windows" version="5.0.0" targetFramework="net472" />

### Guidelines
We have used Visual Studio 2019 community edition to design these sample automation scripts. These scripts are straight forward and can be executed using any test explorer.

We have designed the tests using Page Object Model design pattren with C#. By using this pattern, maintainance of the scripts in feature will be easy.

Since tests were in BDD formate like below, we have used basic cucumber project structure. We have used eclipse IDE for developing this test scripts, so mentioned below all the prerequisites

Test Written:-
1. CreateTimesheet:- It will try to create a timesheer and verify whether the time sheet got created properly or not
2. Create
3. Delete
4. Edit

Project Structure:-
-->Implemented basic Selenium C# project structure. Which has two main folders
1. Pages:- In this folder we have class files for each page
2. Test:- All the tests were designed in a seperate class in this folder

-->A seperate class file with name "BaseDriver.cs" where WebDriver will be initiated and this driver objected will be inherited to all the page class files
-->App.Config - we have used this file to get constant data like browser, app url.. etc



### Prerequisites
1. Visual studio 2019 or later
2. Chrome Browser

### Usage
The following steps will help you run tests:
1. Download/clone this repository into local machine
2. Import the project into Visual Studio
3. Wait for some time to load all the packages
4. Update Chrome driver package based on the version of Chrome Browser in local machine
5. Clean the project and build it
6. Open Test Explorer and start executing the tests based on your requirement
