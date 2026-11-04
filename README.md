# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:
Snap Shot 1: Simple Storage Service (S3)
<img width="1916" height="1017" alt="Screenshot 2026-10-29 152535" src="https://github.com/user-attachments/assets/e4ba6ede-2a44-430e-bd3f-a3e6173552b9" />
 
Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance
<img width="1915" height="1025" alt="Screenshot 2026-10-29 152646" src="https://github.com/user-attachments/assets/60ce91c5-7933-403e-a407-7551c07094a7" />
<img width="1917" height="997" alt="Screenshot 2026-10-29 152747" src="https://github.com/user-attachments/assets/d0248037-39d7-40d6-aa4b-633e45d06ea1" />
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/24fa3d51-cdf8-4533-bb8c-34520979991f" />
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/e1ebccda-ce4d-4565-839e-c32695ecff0d" />
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/fc4dc088-a85f-44ee-b63b-4660ff7197f9" />
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/00dae30e-1fc6-4b90-bc4a-870acfb37d18" />
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/fefd9fa9-a6cd-4801-9bb3-fda517489bb0" />
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/fefd9fa9-a6cd-4801-9bb3-fda517489bb0" />
<img width="1920" height="1080" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/ab7479b6-2d9b-4916-8e4e-7add9757af9b" />
<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/738cbaee-10a9-4bb5-91a8-1e6bc290c41f" />

Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
