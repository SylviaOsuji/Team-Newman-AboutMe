# API Test Automation with Postman & Newman

This project demonstrates API test automation using Postman collections and Newman for execution and reporting.

## Project Structure
- collections/ – Postman collection files
- environments/ – Postman environment files
- newman/ – Newman HTML test reports

## How to Run the Tests
```bash
newman run collections/postman_collection.json \
-e environments/postman_environment.json \
-r htmlextra



## Team-Newman-AboutMe
This is my first repository, I am configuring it to get a notification on slack
