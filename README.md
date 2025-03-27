# Angular Unit Testing Examples

I use this project to test different concepts of unit testing the Angular applications. BTW, you can find decent unit testing styleguide for Angular in corresponding [repository nearby](https://github.com/fyodorio/unit-testing-styleguide).

![unit-testing](https://cdn-images-1.medium.com/max/1600/1*9S01ivk7N1fkh4Tj3MqZgg.gif)

## Getting started

This project was generated with [Angular CLI](https://github.com/angular/angular-cli). Please refer to the documentation to learn about its main commands and features.

# Edit this steps in project

=> Angular Project Code Coverage:
 
-> Download Project angular version and setup in environment variable
 
-> sonar-project.properties (In Project Root folder)
 
sonar.projectKey=Angular_Project
sonar.projectName=Angular_Project
sonar.projectVersion=1.0
sonar.sources=src
# sonar.version=1.0
sonar.sourceEncoding=UTF-8
sonar.exclusions= **/node_modules/**/*
# sonar.exclude=**/node_modules
sonar.typescript.lcov.reportPaths=coverage/lcov.info
sonar.javascript.lcov.reportPaths=coverage/lcov.info
 
 
-> package.json
 
"test": "ng test --code-coverage",
 
-> angular.json
 
"test":
"codeCoverage": true,
 
Command:
- npm install
- npm run test
- sonar-scanner.bat