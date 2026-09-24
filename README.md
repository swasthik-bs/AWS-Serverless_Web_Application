
# AWS Serverless Web Application

### Project Overview

Built a serverless CRUD web application on AWS that allows users to create, read, update, and delete items stored in Amazon DynamoDB.

### Project Architecture:

![Serverless Web Application on AWS Architecture](https://user-images.githubusercontent.com/66474973/228492073-5cd3d975-3439-4ce4-b109-fb33997df3c3.png)

### AWS Services Used

* **Amazon S3** — Hosted the application's static HTML, CSS, and JavaScript files.
* **Amazon CloudFront** — Delivered the frontend globally with low latency through a CDN.
* **Amazon API Gateway** — Exposed REST API endpoints for the frontend to communicate with the backend.
* **AWS Lambda** — Implemented the backend CRUD logic without managing servers.
* **Amazon DynamoDB** — Stored application data using a serverless NoSQL database.
* **AWS IAM** — Managed permissions between Lambda and other AWS resources.
* **Amazon CloudWatch** — Used for Lambda logging and monitoring.

### Implementation

1. Created a DynamoDB table to store application data.
2. Developed a Lambda function to perform CRUD operations on DynamoDB.
3. Created API Gateway endpoints to invoke the Lambda function.
4. Built a static frontend using HTML, CSS, and JavaScript.
5. Hosted the frontend files in Amazon S3.
6. Configured CloudFront to distribute the frontend with lower latency.
7. Configured IAM permissions for secure access between AWS services.
8. Used CloudWatch logs to monitor and troubleshoot Lambda execution.

### Outcome

Successfully deployed a serverless web application on AWS without managing traditional servers. The project provided hands-on experience with serverless architecture, REST APIs, NoSQL databases, IAM permissions, CDN-based content delivery, and integration of multiple AWS services into a complete cloud solution.









