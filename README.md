## API Testing in Postman with Test Cases and Bug Report
1. Create test cases based on the following scenarios in a standard test case format for the Dmoney REST API:
   URL: https://dmoneyportal.roadtocareer.net/

   Admin creates an Agent, 2 random Customers, and a Merchant.
   --> Deposit some money from the SYSTEM account to the Agent.
   --> System account: SYSTEM (range: 10 TK to 10,000 TK)
   --> Agent deposits money to one of the Customers.
   --> Check the Agent's balance.
   --> Send money from one Customer to another Customer.
   --> Withdraw any amount from a Customer to the Agent (range: 10 TK to 10,000 TK).
   --> Check the Customer's balance and transaction statement by trnxId.
   --> Make a payment from the second Customer to the Merchant.
   --> The second Customer checks both balance and transaction statement.
   --> The Merchant checks his balance.
2. Create a Postman collection based on your test cases (from the above 10 scenarios).
   Add negative cases for each request.
3. Write down at least 5 bugs or improvement suggestions in a Google Sheet for the Dmoney API

   
### Technology used
a. node
b. Postman
c. Newman

### API Documentation: 
https://documenter.getpostman.com/view/47684725/2sB3Hhs2Ua
### Test Case Report: 
https://docs.google.com/spreadsheets/d/18zPoAwDkpHqszZR3LdZsXC28sKJ3oVEFmDAE1c_X1DM/edit?usp=sharing
### Bug Report: 
https://docs.google.com/spreadsheets/d/1Gb-Rnw5UllQFXU6-iSxeObjeD13WZyx-/edit?usp=sharing&ouid=117721760905608068339&rtpof=true&sd=true
### Attachment:
   <img width="1366" height="1302" alt="screencapture-file-D-SDET-Assignments-Postman-Assignment-Reports-report-html-2025-08-31-17_25_45" src="https://github.com/user-attachments/assets/ee8462bf-0b17-4387-9536-60177db718f8" />

