# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## Aim: 
  To create cloud storage (S3 Bucket) and launch an EC2 instance in AWS. 

## Procedure: 
### 1. Creating Cloud Storage (S3 Bucket): 
•  Log in to AWS Console → Open AWS Management Console. 
• Go to S3 Service → Click on S3. 
• Create a New Bucket: 
• Click “Create bucket”. 
• Enter a unique bucket name. 
• Choose an AWS region. 
• Set public access settings (default is private). 
• Choose a storage class (Standard, Intelligent-Tiering, etc.). 
• Configure Optional Settings: 
• Enable Versioning if needed. 
• Enable Encryption for security. 
• Create Bucket → Click Create bucket.

### 2. Launching an EC2 Instance: 
• Go to EC2 Service → Open EC2 Dashboard. 
• Launch Instance: 
• Click “Launch Instance”. 
• Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux, Ubuntu, Windows). 
• Select an instance type (e.g., t2.micro for Free Tier). 
• Configure Instance Details (VPC, subnet, auto-assign public IP). 
• Add storage (default is 8 GiB for Linux, modify if needed). 
• Add Tags (e.g., Name: MyEC2Instance). 
• Configure Security Group (Allow SSH for Linux or RDP for Windows). 
• Create/Select Key Pair: 
• Choose existing key pair or create a new key pair. 
• Download the .pem file for SSH access. 
• Launch the Instance → Click Launch.

## Output:
![image](https://github.com/user-attachments/assets/a835827c-82c7-4fc0-8bdf-b36ece83293d)

![image](https://github.com/user-attachments/assets/2846c67d-b3b6-4522-891d-c04eda85b2de)

## Conclusion:
  AWS provides scalable and flexible cloud solutions for both storage (S3) and compute (EC2) services. By completing this experiment, cloud storage was created, and an EC2 instance was successfully launched. 

## Result: 
  Cloud storage (S3 bucket) was successfully created, and an EC2 instance was launched in AWS.
