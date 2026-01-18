# CS-470 Project One – Serverless Full Stack Application (AWS)

## Project Overview

This project demonstrates the migration of a traditional full stack Question & Answer (QnA) web application to a **cloud-based, serverless architecture using Amazon Web Services (AWS)**. The application was redesigned to leverage AWS-managed services in order to improve scalability, performance, security, and maintainability.

The project was completed as part of **CS-470: Full Stack Development II** and focuses on applying cloud development principles, serverless APIs, and elastic infrastructure.

---

## Application Description

The application is a **QnA platform** that allows users to perform full CRUD (Create, Read, Update, Delete) operations on **Questions** and **Answers**.

The original application used a traditional MEAN-style server architecture. In this project, the backend and frontend were fully decoupled and migrated to AWS-native services.

---

## Cloud Architecture

### Frontend
- **Angular** static website
- Hosted on **Amazon S3** using serverless web hosting
- Public access configured through bucket policies
- Frontend communicates directly with AWS APIs

### Backend
- **AWS Lambda** functions used to handle all business logic
- Lambda functions deployed using container-based compute models
- **Amazon API Gateway** exposes RESTful endpoints
- CORS manually configured to allow frontend access

### Database
- **Amazon DynamoDB**
- NoSQL database designed to support CRUD operations
- Separate tables for Questions and Answers
- Fully managed, scalable, and serverless

---

## Key Features

- Serverless frontend hosting using Amazon S3  
- RESTful API built with API Gateway and Lambda  
- Cloud-native database using DynamoDB  
- Full CRUD functionality for Questions and Answers  
- Secure access via IAM roles and policies  
- Elastic scaling with no server management required  

---

## AWS Services Used

- Amazon S3 (Static Website Hosting)  
- AWS Lambda (Serverless Compute)  
- Amazon API Gateway (Serverless API)  
- Amazon DynamoDB (NoSQL Database)  
- AWS IAM (Roles, Policies, and Security)  

---

## Security Implementation

- IAM roles configured to allow least-privilege access  
- Lambda functions granted read/write access to DynamoDB  
- API Gateway permissions configured for Lambda invocation  
- Public access restricted appropriately for S3 frontend hosting  

---

## Deployment Details

- Frontend Angular application built and deployed to S3  
- Backend APIs deployed using the `api` deployment stage  
- Frontend configured to communicate with AWS API endpoints  
- Application successfully tested to confirm full CRUD functionality  

---

## Learning Outcomes

Through this project, I demonstrated the ability to:

- Apply cloud-based development principles  
- Design and deploy serverless full stack applications  
- Migrate backend logic to AWS Lambda microservices  
- Implement secure, scalable APIs  
- Integrate frontend applications with cloud-native backends  

---

## Professional Relevance

This project serves as a portfolio artifact demonstrating real-world experience with:

- AWS serverless architecture  
- Cloud application migration  
- Full stack development  
- RESTful API design  
- Cloud security best practices  

It is directly applicable to **Junior Full Stack Developer**, **Cloud Developer**, and **Backend Developer** roles.

---

## License

This project is for educational and professional portfolio use.
