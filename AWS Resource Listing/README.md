# AWS Resource List Script

## Description

This script automates the process of listing resources in an AWS account. It supports various AWS services and allows users to specify the AWS region and service they are interested in.

## Author

- **Tumbali Venkata Viswas**
- **Version**: v0.0.1

## Supported Services

The script currently supports the following AWS services:

1. **EC2** - Amazon Elastic Compute Cloud
2. **RDS** - Amazon Relational Database Service
3. **S3** - Amazon Simple Storage Service
4. **CloudFront** - Amazon CloudFront
5. **VPC** - Amazon Virtual Private Cloud
6. **IAM** - AWS Identity and Access Management
7. **Route53** - Amazon Route 53
8. **CloudWatch** - Amazon CloudWatch
9. **CloudFormation** - AWS CloudFormation
10. **Lambda** - AWS Lambda
11. **SNS** - Amazon Simple Notification Service
12. **SQS** - Amazon Simple Queue Service
13. **DynamoDB** - Amazon DynamoDB
14. **EBS** - Amazon Elastic Block Store

## Prerequisites

- **AWS CLI**: The AWS Command Line Interface must be installed and properly configured on your machine.

## Usage

Run the script by providing the AWS region and the service you want to list resources for.

```bash
./aws_resource_list.sh <aws_region> <aws_service>
```
Make sure to change permission for the file so that everyone will not change the executable file 

```bash
chmod 771 /path/to/aws_resource_list.sh
