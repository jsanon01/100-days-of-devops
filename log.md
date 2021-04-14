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

**Focus**: Today the lesson was about SNS, SQS, and ECS.

 



**Progress**:
- Create an IAM policy



**Thoughts**: I have learned the model of shared security which means AWS is responsible for the "Security of the Cloud" while customers are responsible for "Security in the Cloud."  


**Work & Resources:**: 

![SNS Messaging Notification](https://github.com/jsanon01/100-days-of-devops/blob/main/images/sns.jpg)

---
# Day 09 - AWS Management

#### Month: Dec 20, 2020

**Focus**: Today the lesson was about CloudTrail, CloudWatch, and CloudFormation.

 

**Progress**:
- Create a CloudWatch event to notify via a SNS topic when an EC2 instance created
- Create a CloudFormation stack using the CloudFormation Designer
- Launch S3 bucket using Infrastructure as Code
- Save and deploy a CloudFormation stack
- View S3 Bucket created by CloudFormation Stack



**Thoughts**: I have learned not only the basics but also the difference between the following AWS services: CloudTrail, Cloudwatch, and CloudFormation. 
- With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. 
- With CloudWatch, you collect and track metrics, monitor log files, set alarms, and automatically react to changes in your AWS resources. 
- With CloudFormation, you can describe your desired resources and their dependencies to launch and configure them together as a stack.


**Work & Resources:**: 

![Cloudwatch](https://github.com/jsanon01/100-days-of-devops/blob/main/images/cloudwatch-event.jpg)

---
# Day 10 - AWS Management

#### Month: Dec 21, 2020

**Focus**: Today it was all ablout AWS CLI which stands for Command Line Interface.

 

**Progress**:
- Getting the raspberry pi up and running (no GUI)
- Install the AWS CLI SDK
- Configure the AWS Command Line Interface (CLI)
- Playing around with the AWS CLI commands



**Thoughts**: It is a pain in the neck when not knowing which commands to use to accomplish some tasks. Becoming familiar with the CLI documention is a plus if I want to save tiime in the future.


**Work & Resources:**: 

[AWS Command Line Interface Documentation](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)

---
# Day 11 - Cloud Fundamentals Project 
## Deploy Static Website on AWS

#### Month: Dec 22, 2020

**Focus**: Today the lesson focused on hosting and deploying a Static Website on AWS. 

 

**Progress**:
- Create an S3 bucket and secures it using IAM Policy
- Create an A record for the website using Route53
- Distribute the web site via CloudFront



**Thoughts**: As I'm getting deeper in AWS best practices, security is at the heart of all AWS core services. Simply said, IAM policies specify what actions are allowed or denied on what AWS resources. On the other hand, S3 bucket policies are attached only to S3 buckets.


**Work & Resources:**: 

[The Travel Blog](https://jeremietravelblog.s3.amazonaws.com/index.html)
![Travel Blog deployed by Cloudfront](https://github.com/jsanon01/100-days-of-devops/blob/main/images/travel_blog.png)

----
# Day 12 - Deployment Infrastructure as Code

## Getting Started with CloudFormation

#### Month: Dec 23, 2020

**Focus**: Today the learning lesson was all about DevOps. 

 

**Progress**:
- Understanding the problem that DevOops is trying to solve
- Understanding Infrastructure as Code
- Understanding Continuous Integration (CI), Continuous Delivery (CD), Continuous Deployment (CD)
- Getting familiar with DevOps tools such as configuration management tools like Ansible and deployment tools like Jenkins, Circle CI, etc...



**Thoughts**: YouTube videos along with Udemy.com, Lynda.com and some interesting articles on Information Technology helped me understand the role and benefits of DevOps in the Cloud Computing environment.


**Work & Resources:**: 

[CI/CD Documentation](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)

----
# Day 13 - Deployment Infrastructure as Code (Continued)

## Working on CloudFormation

#### Month: Dec 24, 2020

**Focus**: Today I learned the basic of CloudFormation. 

 
**Progress**:
- Learned about CloudFormation template and stack of resources
- Create a YML CloudFormation template
- Create a VPC Resource
- Running the template vis the CLI to create the stack
- Use the CLI to verify the stack created and VPC online


**Thoughts**: Thanks again to YouTube videos along with Udemy.com, Lynda.com that helped me understand the role and benefits of DevOps in the Cloud Computing environment.


**Work & Resources:**: 

[CI/CD Documentation](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)

----
# Day 14 - Deployment Infrastructure as Code (Continued)

#### Month: Dec 24, 2020 

**Focus**: Today I learned the importance of the infrastructure diagrams and principles.  

 
**Progress**:
- Create a Lucid Chart Account
- Setting up a Lucid Chart
- Using the diagrams to create a Cloud environment


**Thoughts**: The diagram is as important as descriptive. It helps you to see where the location of services, subnets, route tables, and others within the cloud environment.




**Work & Resources:**: 

![Infrastructure as Code](https://github.com/jsanon01/100-days-of-devops/blob/main/images/iac.jpeg)

----
# Day 15 - Diagram for Hybrid Cloud Environment

#### Month: Dec 25, 2020 

**Focus**: Today the lesson focused on diagrams in a hybrid cloud environment.  

 
**Progress**:
- Getting familiar AWS diagrams
- Using the diagram I created the day before in an architectural manner.


**Thoughts**: Regardless of the business, it has networking infrastructure and requirements. Simply said, converting the business requirements into infrastructure diagrams is one of the DevOps procedures in I.T. Moreover, I have used AWS Direct Connect enabling "customers to have low latency, secure and private connections to AWS for workloads which require higher speed the Internet."




**Work & Resources:**: 

![Hybrid Diagram](https://github.com/jsanon01/100-days-of-devops/blob/main/images/on-premise-day15.jpeg)

----
# Day 16 - Networking Infrastructure

#### Month: Dec 26, 2020 

**Focus**: Today the lesson was more on about Lab meaning "practicing Infrastructure as Code."  

 
**Progress**:
- Create the cloudformation stack which include the VPC
- Update the stack by adding Internet Gatwway, Subnets, and Routing
- Write 'create.sh' and 'update.sh' scripts for creating and updating the stack


**Thoughts**: Hands-on: practicing 'Infrastructure as Code'




**Work & Resources:**: 

![Diagram to Code](https://github.com/jsanon01/100-days-of-devops/blob/main/images/diagram-to-code.jpeg)

----
# Day 17 - Servers & Security Groups

#### Month: Dec 27, 2020 

**Focus**: Today the lesson was more on about Lab meaning "practicing Infrastructure as Code."  

 
**Progress**:
- Creating the Security Groups (SGs)
- Creating Auto-Scaling Group (ASG) and launch configuration
- Getting familiar with interpretion errors, and how to fix them


**Thoughts**: The errors helped strengthen my skills and to go deeper into research on how to fix something that was incorrectly done.



**Work & Resources:**: 

[Security Group Rules](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/security-group-rules-reference.html)

----
# Day 18 - Servers & Security Groups (Continued)

#### Month: Dec 28, 2020 

**Focus**: Today the lesson was to create an environment using AWS CloudFormation  

 
**Progress**:
- Creating the network infrastructure
- Secure the infrastructure
- Creating EC2 instance
- Deploy an application


**Thoughts**: Hands-on and Follow-up.



**Work & Resources:**: 

[AWS CloudFormation & Network Infrastructure](https://computingforgeeks.com/create-aws-network-architecture-with-cloudformation/)

----
# Day 19 - Storage & Databases

#### Month: Dec 29, 2020 

**Focus**: Adding RDS DB to the infrastructure  

 
**Progress**:
- Create an MySQL database
- Configure the database for replication
- Connecting to the database


**Thoughts**: I have learned a lot, simply, by practicing. Also, it is one of the AWS best practices to add the database in the private subnet provide additional security preventing unauthorize access to the data.



**Work & Resources:**: 

[Amazon RDS](https://aws.amazon.com/premiumsupport/knowledge-center/rds-connect-ec2-bastion-host/)

----
# Day 20 - Diagram Architecture (Infrastructure as Code)

#### Month: Dec 30, 2020 

**Focus**: Recap the main concepts  

 
**Progress**:
- Creating VPC
- Creating Internet Gateway
- Creating Subnets
- Creating Route and Route Tables


**Thoughts**: Recapping what I have learned by practicing. 


**Work & Resources:**: 

![Amazon RDS](https://github.com/jsanon01/100-days-of-devops/blob/main/images/task1.png)

----
# Day 21 - Diagram Architecture (Infrastructure as Code)

#### Month: Jan 1, 2021 

**Focus**: Recap the main concepts (Continued)  

 
**Progress**:
- Creating the NAT gateway
- Creating the Private Route table
- Attaching Route table to Subnets


**Thoughts**: Recapping what I have learned by practicing. 



**Work & Resources:**: 

[IAC Diagram](https://geekflare.com/infrastructure-as-code-intro/)

----
# Day 22 - Infrastructure as Code (Diagram Continued)

#### Month: Jan 2, 2021 

**Focus**: Adding RDS DB to the Diagram  

 
**Progress**:
- Create DB subnet group
- Create RDS DB instance


**Thoughts**:  It is AWS best practices to have High Availability when running RDS which needs at least two subnets in two Availability Zones. One subnet for the primary DB and the other for the replicated database.



**Work & Resources:**: 

![RDS in Multi-AZ](https://github.com/jsanon01/100-days-of-devops/blob/main/images/rds_in_AZs.jpeg)

----
# Day 23 - Reviewing Diagram and Infrastructure as Code

#### Month: Jan 3, 2021 

**Focus**: Recapping many concepts 

 
**Progress**:
- Reviewing VPC, Subnets, SGs
- Reviewing AWS Lambda, API Gateway
- Reviewing RDS and its deployment in Multi-AZ environment


**Thoughts**: Recapping what I have learned by practicing. 



**Work & Resources:**: 

[AWS Overview](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/amazon-web-services-cloud-platform.html)

----
# Day 24 - DevOps BootCamp Overview

#### Month: April 12, 2021 

**Focus**: Learning DevOps Concepts

 
**Arrays of DevOps Tools I will work on**:
- Version Control => GIT / GITLAB
- Build Tools => NPM, Maven, Gradle
- CI/CD => Jenkins
- Cloud-IaaS => AWS, Azure, GCP, Digital Ocean, Linode
- Containers => Docker
- Container/Orchestration => Kubernetes
- Infrastructure as Code => AWS CloudFormation, Terraform


**Thoughts**: Below are sets of events that take place in a DevOps Pipeline:

Test --> Build --> Deploy --> Configure --> Maintain 



**Work & Resources:**: 

[AWS Overview](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/amazon-web-services-cloud-platform.html)