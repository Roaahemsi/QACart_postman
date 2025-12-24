# QA Cart – API E2E Testing
#  Project Overview
End-to-End API testing project built using Postman for designing test collections, automated with Newman for command-line execution, and integrated with Jenkins for continuous integration. The project validates API functionality, response accuracy, and reliability, with automated test execution and reporting through a CI pipeline.

# Tools & Technologies
Postman – API test design, assertions, and environments
Newman – Command-line execution of Postman collections
Jenkins – CI pipeline for automated test execution and reporting

# How to Run Tests
newman run QACart_Collection.json -e QACart_Environment.json

# CI Integration
Tests are executed automatically using Jenkins
Newman reports are generated after each run
Results reflect automated API testing within a CI workflow
