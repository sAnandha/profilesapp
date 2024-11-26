# Full-Stack Web Application with AWS Amplify

A full-stack web application built with AWS Amplify integrates front-end and back-end services, including authentication, APIs, and databases. Amplify simplifies deploying and managing the app with features like hosting, serverless functions, and data storage. This solution provides scalability, security, and seamless integration with other AWS services.

## Overview

In this tutorial, you will learn how to create a simple full-stack web application using AWS Amplify.
For detailed instructions,refer to the official AWS tutorial: [AWS tutorial](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb).

 ## You will:

- Build and deploy a React application on AWS
- Use Amplify to add authentication, database integration, and serverless functions
- Capture the signed-up user's email and save it to a DynamoDB table
- Integrate the frontend with AWS cloud resources

## What You Will Accomplish

By the end of this tutorial, you will:

- **Host**: Build and deploy a React application on the AWS global content delivery network (CDN).
- **Authenticate**: Add authentication to your app for user sign-in and sign-out functionality.
- **Database**: Integrate a real-time API, database, and serverless function for data storage.
- **Function**: Implement a Lambda function triggered when a user signs up, saving their email in the database.

## Prerequisites

Before starting this tutorial, ensure you have the following:

- **AWS Account**: If you don’t already have one, follow the [Setup Your Environment](https://docs.aws.amazon.com/amplify/latest/userguide/getting-started.html) tutorial.
- **AWS Profile Configured**: Make sure your AWS profile is configured for local development.
- **Node.js & npm**: Installed on your environment.
- **Git & GitHub**: Familiarity with Git and a GitHub account.

## AWS Experience

- **Level**: Beginner
- **Estimated Time**: 35 minutes
- **Cost**: Free Tier eligible
- **Account Requirements**: AWS Account with administrator-level access (accounts created within the past 24 hours may not have access to required services).

## Services Used

- AWS Amplify
- AWS AppSync
- AWS Lambda
- Amazon DynamoDB



## Application Architecture

The following diagram provides a visual representation of the AWS services used in this tutorial and their interactions. This app leverages AWS Amplify, GraphQL API, AWS Lambda, and Amazon DynamoDB.

<img width="422" alt="Serverless web build" src="https://github.com/user-attachments/assets/4eca10cd-e7c1-4446-8eea-18e8607f5ba3">

---

## Tasks Overview

This tutorial is divided into six tasks. You must complete each task in order before moving on to the next one.

### Task 1: Create Web App (5 minutes)

- Deploy static resources for your web application using the AWS Amplify Console.

### Task 2: Build Serverless Function (5 minutes)

- Build a serverless function using AWS Lambda.

### Task 3: Create Data Table (10 minutes)

- Persist data in an Amazon DynamoDB table.

### Task 4: Link Serverless Function to Web App (5 minutes)

- Deploy your serverless function with API Gateway.

### Task 5: Add Interactivity to Web App (5 minutes)

- Modify your web app to invoke your API.

### Task 6: Clean Up Resources (5 minutes)

- Clean up the resources used in this tutorial to avoid ongoing charges.

---

## Detailed Steps

### 1. Create Web App

- Use the AWS Amplify Console to create a new React app.
- Deploy your static resources to AWS for hosting.

### 2. Build Serverless Function

- Create a Lambda function that will be triggered when a user signs up.
- This function will capture the email address and store it in the DynamoDB database.

### 3. Create Data Table

- Set up a DynamoDB table to store user information.
- Define the schema for storing data in DynamoDB.

### 4. Link Serverless Function to Web App

- Use API Gateway to expose the Lambda function as an API endpoint.
- Link the API to the React frontend to trigger the serverless function when a user signs up.

### 5. Add Interactivity to Web App

- Modify your React frontend to include sign-up functionality and call the API to capture user emails.

### 6. Clean Up Resources

- Once you’ve completed the tutorial, delete the resources you’ve created to avoid unnecessary charges.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
