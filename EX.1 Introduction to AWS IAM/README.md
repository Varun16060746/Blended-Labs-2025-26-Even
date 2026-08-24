# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="1106" height="490" alt="image" src="https://github.com/user-attachments/assets/84c28f00-8db6-4d3a-a3f4-47a091db1887" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1536" height="692" alt="Screenshot 2026-07-31 143617" src="https://github.com/user-attachments/assets/17ee2610-e2e4-4bd6-aa56-6168723719db" />
<img width="1536" height="702" alt="Screenshot 2026-07-31 143655" src="https://github.com/user-attachments/assets/cfc0152e-18f5-4459-99ea-515e8852a5c2" />
<img width="1536" height="697" alt="Screenshot 2026-07-31 143714" src="https://github.com/user-attachments/assets/0ace3040-eb67-4af9-8451-e5433b59c8d7" />



### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**
<img width="1536" height="699" alt="Screenshot 2026-07-31 144602" src="https://github.com/user-attachments/assets/a258e491-c3db-470e-aaa8-df8b6d529d3c" />

<img width="1536" height="706" alt="Screenshot 2026-07-31 144403" src="https://github.com/user-attachments/assets/c5d57267-dd74-4480-b92d-4c1799b87a1b" />
<img width="1227" height="592" alt="image" src="https://github.com/user-attachments/assets/827bdbc5-6e93-4078-b280-b6bcd92f3354" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** VARUN A (212224050057)


**Course:** Introduction to Cloud Computing  

