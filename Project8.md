# Project 8 - AWS VPC using Terraform

In project 7,  VPC, subnets, route tables, and other services in AWS were manually created which can be time consumming, tediuos and and error-prone.

Automation therefore is the way to go and this is where Terraform comes in.

It is a popular IaC tool developed by HashiCorp that allows users to define, provision, and manage infrastructure across various cloud providers and services using a high-level configuration language.

## Steps to execute project 8:

- Leveraging on experiences from projects 1 and 2, I spinned 2 EC2 instances and attach the following IAM roles:

** AmazonVPCFullAccess
** AmazonEC2FullAccess

The steps for this are as shown below:

![1](img/1.png)

![2](img/2.png)

![3](img/3.png)

![4](img/4.png)

![5](img/5.png)

![6](img/6.png)

- I then created the EC2 instance (Ubuntu) and attached the role created earlier to the instance as shown below:

![7](img/7.png)

![8](img/8.png)

- To install terraform,  I 'SSH' into the instance and ran the command shown below:

![9](img/9.png)

- I used the command shown below to clone the repo into the instance and then CD in the cloned repository:

![10](img/10.png)

![11](img/11.png)

- To initialize Terraform, execute the plan and create VPC with Terraform, I ran the commands shown below:

![12](img/12.png)

![13](img/13.png)

![14](img/14.png)

![15](img/15.png)

To validate the created VPC, I refreshed my AWS console, clicked on the created VPC and scroll down to view the Resource Map as shown below:

![16](img/16.png)

## To clean-up the Resources created by Terraform, i executed the command as shown below: 

![17](img/17.png)

![18](img/18.png)

![19](img/19.png)

End of Project8

