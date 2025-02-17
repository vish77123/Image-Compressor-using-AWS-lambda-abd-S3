﻿# AWS-serverless-S3-Image-compressor
Create an image compressor program using AWS lambda, S3, and Pillow. 

### Steps

1) Create a lambda function.
2) Create an S3 bucket.
3) Add S3 as a trigger to the lambda function. 

![alt text](https://github.com/intelliconnect/aws-serverless-S3-Image-compressor/blob/main/Readme%20images/img1.png)

4) Specify ARN :- arn:aws:lambda:ap-south-1:770693421928:layer:Klayers-python38-Pillow:15

![alt text](https://github.com/intelliconnect/aws-serverless-S3-Image-compressor/blob/main/Readme%20images/img%202.png)

5) Add an image to S3 it will automatically create a compressed image to the same bucket. 

![alt text](https://github.com/intelliconnect/aws-serverless-S3-Image-compressor/blob/main/Readme%20images/img%203.png)

###  Documentation on Pillow to adjust compression rate. https://www.geeksforgeeks.org/python-pil-image-resize-method/
