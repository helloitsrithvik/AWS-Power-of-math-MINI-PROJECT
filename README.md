# PowerOfMath — Serverless Calculator

![Personal Project](https://img.shields.io/badge/Personal-Project-orange?style=flat-square)

> 🚀 **Personal Project Showcase by Rithvik**
> Demonstrates full **AWS serverless architecture** using Lambda, API Gateway, DynamoDB, and Amplify.

---

## 📌 Project Overview

**PowerOfMath** is a **personal project** where I built a serverless web application to compute `base^exponent` and store results in **AWS DynamoDB**. This project demonstrates **full AWS integration** with a frontend, backend, API, and secure data storage.

* **Frontend:** HTML page hosted via **AWS Amplify**
* **Backend:** AWS Lambda function that calculates powers and logs results in DynamoDB
* **API:** Exposed via **API Gateway POST endpoint** with **CORS enabled**
* **Security:** IAM role with **least-privilege permissions** for DynamoDB access

---

🎥 Demo

Watch it in action: Watch the above video

---

## 🛠️ Technologies Used

| Component        | AWS Service / Technology    |
| ---------------- | --------------------------- |
| Hosting          | AWS Amplify                 |
| Serverless Logic | AWS Lambda                  |
| API              | API Gateway (POST endpoint) |
| Database         | DynamoDB                    |
| Security         | IAM Roles & Policies        |
| Frontend         | HTML, CSS, JavaScript       |

---

## 💡 Features

* Computes powers of numbers (`base^exponent`)
* Stores all results with timestamp in DynamoDB
* Fully web-accessible via Amplify-hosted frontend
* Secure and restricted DynamoDB access via IAM policy
* Extendable for calculation history or analytics

---

## 🚀 Deployment Instructions

1. **Create DynamoDB Table**

   * Table name: `PowerOfMathDatabase`
   * Primary key: `ID` (String)

2. **Deploy Lambda Function**

   * Upload your file: `PowerOfMathFunction - Lambda`
   * Assign execution role using `Execution Role Policy JSON.txt`

3. **Create API Gateway POST Endpoint**

   * Connect to Lambda function
   * Enable **CORS**

4. **Host Frontend on Amplify**

   * Upload `index.html`
   * Update the JS script with your API Gateway URL

5. **Test the App**

   * Enter base & exponent → see result displayed
   * Check DynamoDB to verify results are logged

---

## 👤 About the Author

Hi, I am **Rithvik**.
This project showcases my **AWS serverless skills**, including Lambda, API Gateway, DynamoDB, IAM, and Amplify hosting. It is a fully deployed, web-accessible personal project demonstrating cloud-native architecture.

