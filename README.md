# CS-470 Full Stack Development II

## Overview

This repository contains coursework and projects completed for **CS-470: Full Stack Development II**.

The course focuses on extending full-stack development concepts into **cloud-based, containerized, and serverless application architectures**. The projects explore how traditional web applications and RESTful services can be designed and deployed using modern cloud technologies.

The primary technologies covered include **Amazon Web Services (AWS)** and **Docker**, with an emphasis on building scalable and maintainable cloud applications.

---

# Course Focus

CS-470 Full Stack Development II explores the transition from traditional full-stack application development to cloud-based architecture.

Major areas of focus include:

* Cloud application development
* Serverless architecture
* RESTful API development
* Containerization
* Cloud storage
* NoSQL databases
* API management
* Application deployment
* Scalability
* Cloud-native development

---

# Technologies

Technologies and services explored throughout the course include:

* Amazon Web Services (AWS)
* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* Amazon S3
* Docker
* RESTful APIs
* JSON
* Serverless Architecture
* Cloud Computing
* Containerization

---

# AWS Lambda

**AWS Lambda** provides serverless computing capabilities that allow application code to execute without requiring a traditional server to be manually provisioned and maintained.

Within the course architecture, Lambda can be used to implement backend functionality that responds to application or API requests.

Serverless development demonstrates concepts such as:

* Event-driven execution
* Backend business logic
* Function-based application architecture
* Serverless computing
* Cloud resource integration
* Scalable backend services

---

# Amazon API Gateway

**Amazon API Gateway** provides an interface between client applications and backend cloud services.

It can be used with AWS Lambda to expose backend functionality through RESTful API endpoints.

A typical serverless request flow can follow this structure:

```text
Client Application
       |
       v
Amazon API Gateway
       |
       v
    AWS Lambda
       |
       v
Amazon DynamoDB / Amazon S3
       |
       v
   JSON Response
       |
       v
Client Application
```

This architecture separates the frontend application from backend services while allowing the application to communicate through HTTP requests.

---

# Amazon DynamoDB

**Amazon DynamoDB** is a NoSQL database service available through AWS.

It can be used by serverless applications to store and retrieve application data without requiring a traditional relational database server.

Concepts associated with DynamoDB include:

* NoSQL database design
* Cloud-based data storage
* Key-based data access
* Application data persistence
* Integration with AWS Lambda
* Scalable database architecture

---

# Amazon S3

**Amazon Simple Storage Service (S3)** provides cloud-based object storage.

S3 can support cloud applications by storing resources and application data outside of the application server.

Cloud storage concepts explored through S3 include:

* Object storage
* Cloud resource management
* Application asset storage
* Separation of application and storage resources
* Cloud-based application architecture

---

# Docker

**Docker** introduces containerization into the full-stack development process.

Containers package an application together with the dependencies and configuration required for it to execute consistently across different environments.

Docker demonstrates concepts including:

* Application containerization
* Portable development environments
* Dependency management
* Container images
* Application deployment
* Environment consistency
* Cloud deployment preparation

A containerized application can follow a structure such as:

```text
Application Source Code
        |
        v
    Dockerfile
        |
        v
   Docker Image
        |
        v
 Docker Container
        |
        v
Application Runtime
```

---

# RESTful API Development

RESTful APIs provide the communication layer between application clients and backend services.

The course explores how cloud services can support API-based application architectures.

Common REST operations include:

| HTTP Method | Purpose       |
| ----------- | ------------- |
| `GET`       | Retrieve data |
| `POST`      | Create data   |
| `PUT`       | Update data   |
| `DELETE`    | Remove data   |

API requests and responses commonly exchange information using **JSON**.

---

# Serverless Architecture

One of the primary concepts explored in this repository is serverless application development.

Instead of maintaining a continuously running backend server, serverless applications can execute backend functionality only when it is required.

A simplified architecture can look like:

```text
Frontend / Client
       |
       v
   REST Request
       |
       v
Amazon API Gateway
       |
       v
    AWS Lambda
       |
       +----------------+
       |                |
       v                v
   DynamoDB             S3
       |                |
       +-------+--------+
               |
               v
         JSON Response
```

This architecture demonstrates how multiple managed cloud services can work together to provide backend functionality.

---

# Cloud-Native Development

Moving application functionality into cloud services introduces several architectural considerations.

These include:

* Scalability
* Availability
* Resource management
* Deployment
* Data storage
* Application performance
* Infrastructure management
* Separation of application components

Cloud-native development encourages applications to be divided into independent services that can be maintained and scaled separately.

---

# Containerized vs. Serverless Architecture

The course provides exposure to both **containerized** and **serverless** approaches to application deployment.

## Containerized Applications

Docker packages the application and its dependencies into a container.

```text
Application
    |
    v
Docker Image
    |
    v
Docker Container
    |
    v
Cloud Environment
```

This approach gives developers greater control over the application's runtime environment.

## Serverless Applications

AWS Lambda allows backend functions to execute without managing a dedicated application server.

```text
API Request
    |
    v
API Gateway
    |
    v
Lambda Function
    |
    v
AWS Services
```

This approach reduces the amount of infrastructure that developers need to manage directly.

---

# Full-Stack Cloud Architecture

The technologies covered in this course demonstrate how a full-stack application can be distributed across multiple cloud services.

```text
            Client Application
                    |
                    v
             RESTful API
                    |
                    v
           Amazon API Gateway
                    |
                    v
              AWS Lambda
                    |
          +---------+---------+
          |                   |
          v                   v
   Amazon DynamoDB       Amazon S3
          |                   |
          +---------+---------+
                    |
                    v
              Cloud Data
```

Docker provides an additional deployment strategy for application components that require containerized environments.

---

# Skills Demonstrated

This coursework demonstrates experience with:

* Full-Stack Development
* Cloud Computing
* Amazon Web Services
* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* Amazon S3
* Docker
* Containerization
* Serverless Computing
* RESTful API Development
* JSON
* NoSQL Databases
* Cloud Storage
* Backend Development
* API Integration
* Application Architecture
* Cloud Application Architecture
* Scalable Application Design
* Software Deployment

---

# Learning Objectives

Through CS-470 Full Stack Development II, the primary learning objectives include:

* Understanding cloud-based application architecture
* Developing serverless backend functionality
* Building RESTful cloud APIs
* Working with AWS managed services
* Understanding NoSQL cloud databases
* Using cloud object storage
* Containerizing applications with Docker
* Comparing traditional, containerized, and serverless deployment approaches
* Designing applications for scalability
* Understanding how full-stack applications can be migrated to cloud infrastructure

---

# Repository Purpose

This repository serves as a portfolio of work completed while studying **cloud-based full-stack software development**.

It demonstrates the progression from traditional full-stack development concepts toward modern cloud architecture using AWS and Docker.

The coursework provides practical exposure to technologies commonly used for developing scalable web applications, backend APIs, serverless services, and cloud-hosted software.

---

# Author

**Darius Quick**

Computer Science graduate with a Software Engineering focus.

This repository represents coursework completed as part of **CS-470 Full Stack Development II**, with an emphasis on cloud computing, serverless development, RESTful APIs, AWS services, and Docker containerization.
