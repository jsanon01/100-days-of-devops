# Day 01 - Introduction to Cloud Computing

#### Month: Dec 12, 2020

**Focus**: The learning focuses on understanding the Cloud Computing ecosystem and as well as its on-demand availability, scalability, and elasticity.

**Progress**:
- Types of Cloud Computing
- Deployment Models 
- Benefits of Cloud Computing
- Amazon Web Services AWS Overview

**Thoughts**: Today, I have learned the basic concepts about Cloud Computing and how it is useful in this 21st century.
In addition, Cloud Computing uses computer system resources, especially data storage and computing power, without direct active management by the user.


**Work & Resources:**:

[Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)

---
# Day 02 - Introduction to Virtual Private Cloud

#### Month: Dec 13, 2020

**Focus**: Today, the learning lesson was on VPC and its key concepts.

**Progress**:
- Virtual Private Cloud (VPC) — A virtual network dedicated to your AWS account.
- Types of Subnets 
- VPC endpoints
- Internet Gateway
- Route Table
- CIDR Block

**Thoughts**: Today, it is all about VPC as a Networking Service and how it is related logically and physically to its components. 


**Work & Resources:**: 

![Virtual Private Cloud](https://github.com/jsanon01/100-days-of-devops/blob/main/images/custom-vpc.jpeg)

[AWS VPC Documentation](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)

---
# Day 03 - Foundational and Compute Service

#### Month: Dec 14, 2020

**Focus**: Today, the learning lesson emphasized compute, storage, auto scaling and load balancing.

**Progress**:

- EC2-Basics:
	Learned how to create EC2 instance
	Associate the instance with a Security Group (SG) allowing SSH traffic from any IP
	Create a snapshot of the EBS volume attached to the EC2 Instance
	Create an AMI using the snapshot
	Create a new instance using the AMI

- Storage:

	Learn about the different storage class
	Create an EBS volume and attack it to instance
	Create an EFS filesystem and mount it to instance

- S3 and IAM Role:

	Create an S3 bucket
	Create IAM Role with EC2 Service
	Attach AmazonS3FullAccess to policy
	Attach role when creating launch configuration

- Auto scaling and Load Balancing

	Create Launch Configuration 
	Create AutoScaling Group using the Launch Configuration
	Create Target Groups
	Create Elastic Load Balancer and have load balancer serves traffic to the instance
	Verify you can see webapp from your browser


**Thoughts**: "Learning by Doing" is nothing esle than hands-on. I have realized that the best way to learn and gain experience in I. T. field is through hands-on.  


**Work & Resources:**:

![Lab Design](https://github.com/jsanon01/100-days-of-devops/blob/main/images/day-1-1.png)

---

# Day 04 - Foundational and Compute Service

#### Month: Dec 15, 2020

**Focus**: The learning was focused on Lambda function and its parameters. I have put careful consideration on how to start and stop the instance. I even played around with API gateway that called the lambda function to bring the intance up/down.



**Progress**:
- Learn the basic of Lambda
- Review the concepts of event source downstream resources, and log stream
- Create Lambda function using the Python runtime in the editor
- Creaye IAM roles to give not only Lambda access to EC2 but also CloudWatch
- Code the lambda function to start/stop an EC2 instance
- Playing around with environment variables


**Thoughts**: Today, it was all about Lambda function. I have noticed that AWS Lambda  and API Gateway go hand in hand. Needless to say, they are the cores of Serverless Architecture. 


**Work & Resources:**: 

![AWS Lambda](https://github.com/jsanon01/100-days-of-devops/blob/main/images/start-stop-ec2-lambda.jpg)

---
# Day 05 - AWS Management

#### Month: Dec 16, 2020

**Focus**: Today the learning aimed to better understand the AWS terminal meaning the AWS Command Line (CLI) Interface.



**Progress**:
- Getting the Raspberry Pi up and running with no GUI installed
- Install the AWS CLI SDK
- Getting familiar with the AWS CLI commands


**Thoughts**: It is sometimes stressful when not knowing which commands to type to accomplish some tasks. It is great to spend some time to reading the CLI documention which will be not only one's best friend but also time-saving.  


**Work & Resources:**: 

![AWS CLI on Raspberry Pi](https://github.com/jsanon01/100-days-of-devops/blob/main/images/aws_cli.png)

[AWS Command Line Interface Documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)

---
# Day 06 - Storage & Content Delivery

#### Month: Dec 17, 2020

**Focus**: Among AWS services I have been working on today, I can state the following: S3 for storage and web hosting, DynamoDB for No SQL DB, RDS which is short for Relational Database Service, and CloudFront to speed up static and dynamic web content delivery. 



**Progress**:
- Create a NoSQL database using DynamoDB
- Create a PostgreSQL database instance using RDS
- Connect and query the databases
- Create a S3 bucket and upload a simple web site to the bucket
- Create a CloudFront distribution for the website


**Thoughts**: The beauty of a network (LAN/WAN) is the connection of the devices. Moreover, the  interaction among AWS services makes hands-on funnier, as far as I'm concerned.  


**Work & Resources:**: 

[Introduction to CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)

---
# Day 07 - Security

#### Month: Dec 18, 2020

**Focus**: Today the learning was on Security. As par of AWS Well-Architected Framework, security stressed the needs on applying best practices to keep your environment and the applications running in the Cloud in a secured manner. 



**Progress**:
- Create an IAM policy



**Thoughts**: I have learned the model of shared security which means AWS is responsible for the "Security of the Cloud" while customers are responsible for "Security in the Cloud."  


**Work & Resources:**: 

[AWS Best Practices](https://d1.awsstatic.com/whitepapers/aws-security-best-practices.pdf)

---
# Day 08 - Messaging & Containers

#### Month: Dec 19, 2020

**Focus**: Today the lesson was on SNS, SQS, and ECS.

 



**Progress**:
- Create an IAM policy



**Thoughts**: I have learned the model of shared security which means AWS is responsible for the "Security of the Cloud" while customers are responsible for "Security in the Cloud."  


**Work & Resources:**: 

[AWS Best Practices](https://d1.awsstatic.com/whitepapers/aws-security-best-practices.pdf)
