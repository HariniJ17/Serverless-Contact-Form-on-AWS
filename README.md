# Serverless-Contact-Form-on-AWS

A **Serverless Contact Form** built using AWS services including **API Gateway**, **Lambda**, **DynamoDB**, and **SES**.  
This project allows users to submit messages via a web form, stores messages in DynamoDB, and sends email notifications using SES.

---


## Project Overview

This project implements a serverless contact form that:  
1. Accepts user input (Name, Email, Message) via a web form.  
2. Sends the data to **AWS API Gateway** using HTTP POST.  
3. Triggers a **Lambda function** that:  
   - Stores the message in **DynamoDB**  
   - Sends an email notification using **AWS SES**  

The serverless architecture ensures **scalability**, **low cost**, and **minimal server maintenance**.

---

## Architecture & Flow

**User → HTML Form (Frontend) → API Gateway → Lambda →**  
- **DynamoDB** (store message)  
- **SES** (send email)  

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **AWS Services:**  
  - API Gateway (HTTP POST endpoint)  
  - Lambda (Python/Node.js)  
  - DynamoDB (NoSQL database)  
  - SES (Simple Email Service)  

