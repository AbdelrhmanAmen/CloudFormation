# Purpose

> The main idea is to use AWS native service for infrastructure as code (IAC) which is __*CloudFormation*__, to create a collection of related AWS resources.
---
## Scenario 
> - Build a VPC with one private subnet and one public subnet.
> - Create an EC2 instance inside the public subnet.
> - Allow ssh and http on the EC2 instance.
---
## Steps to define resources
> - Create the virtual private cloud (VPC) and its CIDR block.
> - Define one public subnet (apply auto assign for public ip) and one private subnet / each subnet will be in a different availability zone.
> - Create security group that will be attach for the instance. 
> - Create internet gateway.
> - Build route table and create routing record for the gateway.
> - Link the route table to the public subnet.
> - Create the EC2 instance.
---
- [x] Voilà the infrastructure is ready now.
