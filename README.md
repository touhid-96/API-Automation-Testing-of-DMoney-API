# API-Automation-Testing-of-DMoney-API

## Technology and Tool Used
- Postman
- Newman

## Scenario
1. Admin creates an agent and random 2 customers. Admin email: admin@roadtocareer.net/ Pass: 1234
2. Deposit some money from SYSTEM account to the agent. System account: SYSTEM (range 10 tk to 10000 tk)
3. Agent deposit to any of 1 customer
4. Check agent balance
5. Then withdraw any amount by the customer from the agent (range 10 tk to 10000 tk)
6. Then the customer checks balance
7. Then send money to the other customer
8. Then from the another customer payment to this merchant: 01712121212
9. Then the second customer will check both balance and statement
10. Then the merchant will check his own balance

## How to run this project
- clone this project
- hit the following command:
  - npm init -y 
  - npm i newman 
  - npm i newman-reporter-htmlextra 
  - npm i 
  - npm test 

## Prerequisite
- Node.js must be installed

## API Documentation
https://documenter.getpostman.com/view/32159205/2sA35G52qV

## Test Case
https://docs.google.com/spreadsheets/d/1Ur-Xil7NBmVHBf1PiQE9weY8ShV_R0-NBo7UuwXAQGI/edit?usp=drive_link

## Issue report
https://docs.google.com/spreadsheets/d/1cIrecIi7kHHbld4l9WrvSLbQB_MHNwP5-5h3sXNiQrE/edit?usp=drive_link

## Output!
![Screenshot (31)](https://drive.google.com/file/d/1qyBXVSc2BVH7rxmdpKR0xm9rZlK9_ynw/view?usp=drive_link)
