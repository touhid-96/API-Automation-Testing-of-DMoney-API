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
  1. `npm init -y` 
  2. `npm i newman`
  3. `npm i newman-reporter-htmlextra`
  4. `npm i`
  5. `npm test`

## Prerequisite
- Node.js must be installed

## API Documentation
https://documenter.getpostman.com/view/32159205/2sA35G52qV

## Test Case
https://docs.google.com/spreadsheets/d/1Ur-Xil7NBmVHBf1PiQE9weY8ShV_R0-NBo7UuwXAQGI/edit?usp=drive_link

## Issue report
https://docs.google.com/spreadsheets/d/1cIrecIi7kHHbld4l9WrvSLbQB_MHNwP5-5h3sXNiQrE/edit?usp=drive_link

## Output
![newman_report](https://github.com/touhid-96/API-Automation-Testing-of-DMoney-API/assets/29010371/0ba694cf-d8bb-4952-bdc0-f0fdc57e24f0)

