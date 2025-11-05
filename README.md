# AWS-Powered-Travel-Diary-App

A cloud-powered web app to store and share travel memories securely.

## Overview

Travel Diary App is a secure and scalable web application built using AWS Amplify.
It allows users to:
 Create an account & log in securely,
 Upload and store travel photos & notes,
 View their personal travel memories anytime,
 Store content securely in the cloud.

This project demonstrates full-stack cloud development using serverless architecture.

## Features
## Feature	Description
🔐 User Authentication	Login & Signup using AWS Cognito
🗂 Secure File Uploads	Store images safely using AWS S3
🌍 Diary Entries	Add travel notes & memories
☁️ Cloud Hosted	Frontend deployed on AWS Amplify Hosting
📦 (Optional)	NoSQL data storage using DynamoDB

## Note: DynamoDB was implemented initially and removed later to optimize cost while learning AWS workflows.

## Architecture
React Frontend → AWS Amplify → Cognito (Auth)
                                →
                            S3 Bucket (Photos)
                                →
                     (Optional) DynamoDB (Notes)

## Tech Stack
Component	Technology
Frontend	React.js
Cloud Backend	AWS Amplify
Authentication	Amazon Cognito
Storage	Amazon S3
Optional Database	DynamoDB (initial phase)

## Setup & Deployment Steps
## 1️⃣ Install Amplify CLI
```bash
npm install -g @aws-amplify/cli
amplify configure
```
## 2️⃣ Initialize Amplify
```bash
amplify init
```

## 3️⃣ Add Authentication
```bash amplify add auth
amplify push
```

## 4️⃣ Add Storage (S3)
```bash amplify add storage
amplify push
```

## 5️⃣ Run App Locally
```bash
npm install
npm start
```

## 6️⃣ Deploy to Cloud
```bash
amplify publish
```

## Folder Structure
```bash /src
  /components
  App.js
  aws-exports.js  ← Amplify config file
/public
package.json
README.md
```
## Key Learnings

Hands-on experience with AWS serverless tools

Secure authentication with Cognito

Cloud storage & permissions with S3

Hosting a production web app with Amplify

Practical understanding of real-world cost optimization (removed DynamoDB when not required)


## 👩‍💻 Developer

Ayushi Nagpure
Cloud & AI Enthusiast 
