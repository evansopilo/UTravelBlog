# UTravel Blog
The aim of this project is to deploy a static website on AWS and accelerate its delivery using AWS CloudFront which is a  Cloud CND by AWS, this project is accomplished as part of the Udacity Cloud Developer Nano degree. 

## Project Overview
The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. The whole project has two major intentions to implement:
Hosting a static website on S3 and Accessing the cached website pages using CloudFront content delivery network (CDN) service. Recall that CloudFront offers low latency and high transfer speeds during website rendering.
Note that Static website hosting essentially requires a public bucket, whereas the CloudFront can work with public and private buckets.

## Dependencies
### Cloud Services
1. Amazon Web Services S3 - Resource hosting and deployments
2. AWS CloudFront - CDN for SPA
3. AWS EKS - Backend API
4. AWS DynamoDB - Persistent Datastore
5. AWS Cognito - User Authentication

## Performance Tracking and DevOps Tools:
1. AWS CloudWatch - Performance and Health checks
2. Sentry - Bug Reporting
3. Google Analytics - Usage Reporting

## Frameworks:
1. Ionic (Javascript) (Frontend)
2. Node.js (Javascript) (Backend)


