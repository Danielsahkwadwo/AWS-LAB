# AWS-LAB
# Automating Creation of IAM Resources LAB

## Overview
This project provides an automated setup for creating AWS Identity and Access Management (IAM) resources. It simplifies the process of managing IAM users, groups, and permissions in AWS environments.

## Features
- Automated creation of IAM users and groups
- Assignment of permissions through policies
- Integration with AWS EventBridge and Lambda for event-driven automation

## Prerequisites
- AWS account
- AWS CLI installed and configured
- Permissions to create IAM resources in your AWS account

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iam-automation-lab.git
   cd iam-automation-lab
   ```

2. Deploy the CloudFormation template:
   ```bash
   aws cloudformation deploy --template-file iam-setup.yaml --stack-name IamAutomationLab
   ```

## Usage
- Monitor the creation of IAM resources through AWS CloudFormation console.
- View logs and events in AWS CloudWatch.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or suggestions.

## License
This project is licensed under the MIT License.
