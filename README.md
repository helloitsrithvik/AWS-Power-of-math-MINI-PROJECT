PowerOfMath — Serverless Calculator

🚀 Personal Project Showcase by Rithvik
Demonstrates full AWS serverless architecture using Lambda, API Gateway, DynamoDB, and Amplify.

📌 Project Overview

PowerOfMath is a personal project where I built a serverless web application to compute base^exponent and store results in AWS DynamoDB. This project demonstrates full AWS integration with a frontend, backend, API, and secure data storage.

Frontend: HTML page hosted via AWS Amplify

Backend: AWS Lambda function that calculates powers and logs results in DynamoDB

API: Exposed via API Gateway POST endpoint with CORS enabled

Security: IAM role with least-privilege permissions for DynamoDB access

🛠️ Technologies Used
Component	AWS Service / Tech
Hosting	AWS Amplify
Serverless Logic	AWS Lambda
API	API Gateway (POST endpoint)
Database	DynamoDB
Security	IAM Roles & Policies
Frontend	HTML, CSS, JavaScript
💡 Features

Computes powers of numbers (base^exponent)

Stores all results with timestamp in DynamoDB

Fully web-accessible via Amplify-hosted frontend

Secure and restricted DynamoDB access via IAM policy

Extendable for calculation history or analytics

🚀 Deployment Instructions

Create DynamoDB Table

Name: PowerOfMathDatabase

Primary key: ID (String)

Deploy Lambda Function

Upload PowerOfMathFunction - Lambda

Assign execution role using Execution Role Policy JSON.txt

Create API Gateway POST Endpoint

Connect to Lambda function

Enable CORS

Host Frontend on Amplify

Upload index.html

Update JS script with your API Gateway URL

Test the App

Enter base & exponent → see result displayed

Check DynamoDB to verify results are logged

🎥 Demo

This is my personal project. Watch it in action:


👤 About the Author

Hi, I am Rithvik.
This project showcases my AWS serverless skills, including Lambda, API Gateway, DynamoDB, IAM, and Amplify hosting. It is a fully deployed, web-accessible personal project demonstrating cloud-native architecture.
