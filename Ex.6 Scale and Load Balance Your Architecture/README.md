# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture

Author : VARUN A

Reg no : 212224050057

Date : 28-08-2026

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

1.Launched a new EC2 instance named Web Server in the N. Virginia region using Amazon Linux 2023 AMI and t2.micro instance type.

2.Enabled termination protection and stop protection, configured a security group, and added a user data script to install and start an Apache web server.

3.Monitored the instance using status checks, CloudWatch metrics, and system logs to ensure it was running properly.

4.Modified the security group to allow HTTP (port 80) traffic and accessed the web server using the public IP address.

5.Resized the instance to t2.small, increased the EBS volume size, explored EC2 service quotas, tested stop protection, and finally stopped the instance.

## Output Screenshots 

<img width="1917" height="1037" alt="Screenshot 2026-08-26 212839" src="https://github.com/user-attachments/assets/6fa53f57-2df3-4ee5-a38b-420e57388b52" />

<img width="1918" height="1032" alt="Screenshot 2026-08-26 213055" src="https://github.com/user-attachments/assets/778bcfb6-985a-4e20-b152-c30d859f61f9" />

<img width="1918" height="1042" alt="Screenshot 2026-08-26 213903" src="https://github.com/user-attachments/assets/bd149dab-a548-4cdb-92e3-00ba68599c8a" />

<img width="1919" height="910" alt="Screenshot 2026-03-12 212615" src="https://github.com/user-attachments/assets/601f9ba0-ecea-476f-a486-3ec2fa5b918d" />

<img width="1919" height="905" alt="Screenshot 2026-03-12 214730" src="https://github.com/user-attachments/assets/e97c5e16-3960-4a8b-9cc4-8715d635a361" />

<img width="1918" height="1040" alt="Screenshot 2026-08-26 220801" src="https://github.com/user-attachments/assets/bd808b19-f0d8-49ae-bb81-f37623650c02" />

<img width="1918" height="1033" alt="Screenshot 2026-08-26 224049" src="https://github.com/user-attachments/assets/15c8d3f2-dde2-4b69-8b90-13324641b82c" />






## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
