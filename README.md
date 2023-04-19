# Selenium Java TestNG Maven Allure Report Playground project

## Pre-requirement for this project
```
- JDK Install & Set up Environment variable
- Maven Set up Environment variable
```

## Set up project
```
- Clone from the github into your IDE (IntelliJ)
- mvn clean compile
- mvn clean test 
```

## How to execute test suite 
```
- mvn clean test
```

## Generate Allure Report
```
- allure serve "allure-results path"
- Example: allure serve allure-results
```

## Set up Action 
```
- Create Java Maven build.yml file
- Github > Settings > Action Generel > Workflow permissions > Select 
    Read and Write Permissionm 
- Create Github page with Jeklin
```