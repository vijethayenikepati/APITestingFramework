## Overview

This project is a REST API test framework built to automate the testing of RESTful APIs 
using JUnit 5, Rest-Assured, and Cucumber. The framework supports parallel test execution
to enhance efficiency and reduce execution time. It is developed using Maven and leverages
Java 17 features.

## Prerequisites
- Java 17
- Maven 3.x

## Setup

1. Clone the Repository:

   git clone https://github.com/vijethayenikepati/RestAssuredAssignment.git

2. For Run Tests:
   ```sh
   mvn clean install

3. For Parallel execution:
   ```sh
   mvn verify

After running the tests, the reports generated found at `target/cucumber-reports.html` directory.
Open the report using a web browser to review the results.

Working in IDE:

1.Navigate to "src/test/java/com/api/runners"
2.Go to TestRunner.java and run
3.Rerun Failed Tests using FailedRunner.java

   

