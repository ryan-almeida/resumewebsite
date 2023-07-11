# Simple Resume Website Project

This is an introductory Hands-On Project I worked on to develop practical skills in the cloud, using AWS. Feel free to read along and attempt it yourself. We will build a simple static website using beginner friendly and widely used services in AWS, such as S3, Cloudfront, and Route 53

## Architecture and High Level Design

The website will be built using the following architecture: <br><br>
![Alt text](reference-architecture.jpeg)

## Learning Outcomes

This project helped me understand the following concepts: <br>
1) How to host a simple, static website on AWS using S3
2) How to increase security and availability by deploying it on CloudFront
3) How to make it more accesible through the web browser by using Route 53 and Amazon Certificate Manager (ACM)

## Setup
### 1. Upload HTML file into S3 Bucket 
We first need to create a basic HTML webpage to show our resume. You can use free resources from the internet or customize the "detailed-resume.html" file in the repository. Do not waste too much time formatting since HTML/CSS is not the main focus of the project. The website can always be modified later. <br>

Login to your AWS Managemnt Console and go to S3 > Create Bucket. Enter your desired bucket name (make sure you select a unique name!):
