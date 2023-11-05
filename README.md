# static-webpage-serverless
Static Feedback Page with Serverless Architecture
## Project Details
This project walks you through the steps to configure a static web application which allows you to submit a message by attaching an image. This response will be collected in the DynamoDB table and the corresponding image will be stored in the S3 Bucket.
In this project infrastructure, you will use only the serverless services to deploy the web page.
User is able to fill the data and upload the image which is kept on S3 Bucket and the data is stored in the DynamoDB table.

## Scenario Details
Your company ABC has recently ended up a project to build a web application for company XYZ which aims to conduct a market research of their product before they could start their startup.
App allows users to write their take about the idea and provide any suggestions/ improvements to the product. On submitting the Form, the data should be added in a DynamoDB table and the image uploaded should be added in the S3 bucket.
The webpage deployment should be automated so that clients can make changes to the webpage and deploy them easily.
The condition is that the entire project should be done in a serverless architecture.

## Who is this project for?
- Anyone who wants to host a static web application on a AWS Serverless Architecture.
- AWS Certified Developer - Associate, AWS Certified DevOps Engineer Professional, AWS Certified SysOps Administrator Associate.

##  Prerequisites
- Knowledge of AWS services
- Serverless
- S3
- API Gateway
- Lambda
- DynamoDB
- Basic knowledge of HTML, CSS, JavaScript

## Task Details
1. Launching Lab Environment
2. Creating a DynamoDB table
3. Creating a image storing S3 bucket and adding bucket policy
4. Creating a S3 bucket to store your web page content
5. Host the static webpage
6. Creating a Lambda function
7. Creating a Rest API
8. Creating a Resource and Method for the API
9. Testing the API
10. Enabling the CORS and Deploying the API
11. Modify the index.html page to add the API Gateway endpoint
12. Testing the Web Page
13. Validation of the Lab
14. Clean up Resources
