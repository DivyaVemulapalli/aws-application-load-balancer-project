# AWS Application Load Balancer (ALB) Project

##  Project Overview

Implemented an AWS Application Load Balancer (ALB) to distribute incoming HTTP traffic across multiple Amazon EC2 instances deployed in different Availability Zones. This project demonstrates high availability, fault tolerance, and scalable web architecture using AWS.

##  AWS Services Used

* Amazon EC2
* Application Load Balancer (ALB)
* Target Groups
* Amazon VPC
* Security Groups

##  Project Objectives

* Deploy multiple web servers on Amazon EC2
* Configure an Application Load Balancer
* Distribute traffic across multiple instances
* Understand high availability concepts
* Implement basic load balancing architecture

##  Steps Followed

1. Created a custom VPC with public subnets in two Availability Zones
2. Launched two Amazon EC2 instances in separate subnets
3. Installed and configured Apache web server on both instances
4. Created custom web pages on each server
5. Created a Target Group and registered both EC2 instances
6. Configured health checks for the target group
7. Created an Application Load Balancer
8. Associated the ALB with the target group
9. Verified traffic distribution using the ALB DNS name

##  Architecture

User → Application Load Balancer → EC2 Instance 1


                                         → EC2 Instance 2

##  Outcome

Successfully configured an Application Load Balancer to distribute incoming HTTP requests across multiple EC2 instances. Verified load balancing functionality by accessing different web pages through the ALB DNS endpoint.

##  Key Learnings

* Application Load Balancer (ALB)
* Target Groups
* Health Checks
* High Availability
* Load Balancing Concepts
* Amazon VPC Networking
* Web Server Deployment
* Scalable Cloud Architecture

##  Future Enhancements

* Add Auto Scaling Group integration
* Implement HTTPS using AWS Certificate Manager
* Configure Route 53 custom domain
* Deploy instances in private subnets
* Implement monitoring using CloudWatch
