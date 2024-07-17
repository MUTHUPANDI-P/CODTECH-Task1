Name : Muthupandi P

Company : CODTECH IT SOLUTIONS

ID : CT4CC2717

Domain : Cloud Computing

Duration : June 20 to July 20 2024

Mentor : Neela Santhosh kumar

# Deploying a Web Application on AWS
This project demonstrates the deployment of a simple web application using Amazon Web Services (AWS). The goal is to provide a foundational understanding of cloud deployment, covering essential tasks such as setting up a server, configuring a web application, and utilizing AWS services like EC2 and S3.
## Project Description
In this project, you will learn how to deploy a web application on AWS through the following steps:
### Create an EC2 Instance
1. Log into the AWS Management Console.
2. Navigate to the EC2 Dashboard and click "Launch Instance."
3. Select an Amazon Machine Image (AMI), such as Amazon Linux 2.
4. Choose an instance type, like t2.micro, which is eligible for the free tier.
5. Configure instance details, ensuring the appropriate VPC and subnet are selected.
6. Add storage if necessary.
7. Set up security groups to allow HTTP (port 80) and SSH (port 22) access.
8. Review and launch the instance, creating or selecting an existing key pair for SSH access.
### Upload Application Files to S3

1. Navigate to the S3 Dashboard in the AWS Management Console.
2. Create a new S3 bucket or select an existing one.
3. Upload the web application files to the S3 bucket, maintaining the proper folder structure.
4. Set appropriate permissions to allow the EC2 instance to access the files.
### Connect to the Instance using MobaXterm

1. Download and install MobaXterm if not already installed.
2. Use MobaXterm to connect to the EC2 instance by entering the public DNS or IP address.
3. Provide the key pair for SSH access when prompted.

### Load Application Files from S3 to the Server

1. Install the AWS CLI on the EC2 instance.
2. Configure the AWS CLI with your credentials.
3. Copy files from the S3 bucket to the EC2 instance using the appropriate AWS CLI commands.

### Unzip the Files

1. Install the unzip utility if not already installed.
2. Navigate to the directory where the files were copied.
3. Unzip the application files.

### Run the Web Application

1. Navigate to the application directory.
2. Ensure that all necessary dependencies and environment variables are set up.
3. Start the web application using the relevant command for your application.
4. Verify that the application is running by accessing the public IP address of the EC2 instance in a web browser.

## Technologies Used

- Amazon Web Services (AWS)
  - EC2
  - S3
- MobaXterm
- AWS CLI

## Conclusion

This project provides a hands-on approach to understanding the basics of deploying web applications on AWS. It covers essential skills in server setup, file management, and application deployment, serving as a valuable resource for anyone looking to get started with cloud computing.

![Screenshot 2024-07-17 153439](https://github.com/user-attachments/assets/f4b5dc7e-219c-41d6-9b80-401b7f2fbddb)

![Screenshot 2024-07-17 153412](https://github.com/user-attachments/assets/1e856b96-8bc5-44b7-ad03-2cdd222a0124)

![Screenshot 2024-07-17 153859](https://github.com/user-attachments/assets/9d6ad3f9-853e-4951-952c-95065e51b3c3)

![Screenshot 2024-07-17 153938](https://github.com/user-attachments/assets/cbee265a-b592-4e6a-977f-bb0f15a67c1e)





