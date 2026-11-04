Cloud-storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
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
 <img width="1915" height="1025" alt="Screenshot 2026-10-29 152646" src="https://github.com/user-attachments/assets/f948ddce-c3a5-4a19-bb26-a0cf918108be" />


Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance
<img width="1917" height="997" alt="Screenshot 2026-10-29 152747" src="https://github.com/user-attachments/assets/921b908e-1386-472f-8f3b-80205846040e" />
<img width="1900" height="1020" alt="Screenshot 2026-10-29 152851" src="https://github.com/user-attachments/assets/37c98d03-21dd-4ed5-986d-ab038bc0f143" />
<img width="1917" height="1020" alt="Screenshot 2026-10-29 152941" src="https://github.com/user-attachments/assets/44595109-ff7a-4602-ac44-fc8512b4922f" />
<img width="1916" height="1021" alt="Screenshot 2026-10-29 153340" src="https://github.com/user-attachments/assets/013f8c83-5f6a-4eea-a80e-dbe7308958d7" />
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/df6af813-b125-4624-877a-2d4480ad6ebf" />
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/bbbc2cfd-ab7b-48c5-b6f1-4115e1d34f17" />
<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/6f996552-5f4b-4b25-9a46-a23c42e8893b" />
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/d330663a-affb-4688-80ea-c4c559e4a701" />
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/ab13ac5f-e254-4ed4-8322-fe9680c4af9f" />
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/68c7e67b-f06e-4439-ac71-af174844e7bb" />
<img width="1920" height="1080" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/aef18704-abf2-44df-97a7-fe39faa70b0f" />
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/6c26116d-cb34-4aba-b755-2368032727be" />
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/4c7853d0-9852-434d-8d54-328dff179052" />
<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/25693941-9ea3-4af2-9b6c-cd09030f4613" />
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/e30be2c4-4e5d-4dfd-b4e4-becc4870a2dc" />
<img width="1920" height="1080" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/d205c648-dc35-404d-94ae-3f5cf37a045e" />
<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/2e50c064-d54b-4307-a463-6d712f600dbb" />
<img width="1920" height="1080" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/7921eb40-0133-421b-a37c-dc664041a8be" />
<img width="1920" height="1080" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/19f95cc6-feee-47e2-99fe-e2ab78725212" />
<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/1fe20d27-84b3-4bf2-af9f-14b3b8d17d0a" />
Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
