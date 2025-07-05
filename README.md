# Cloud_computing1
**COMPANY**      : CODTECH IT SOLUTIONS
**NAME**         : DEEPAK 
**INTERN ID**    : CT04MRV
**DOMAIN**       : CLOUD COMPUTING 
**DURATION **    : 4 MONTHS 
**MENTOR**       : NEELA SANTOSH 
**DESCRIPTION**  : 
**Task: Create and Configure Cloud Storage on AWS S3**

This task involves creating and configuring cloud storage using Amazon Web Services (AWS) Simple Storage Service (S3). AWS S3 is a highly scalable, secure, and durable object storage service used for storing any type of data, such as documents, images, videos, and application backups. It plays a vital role in cloud-based infrastructure, offering high availability, data encryption, and flexible access control features.

The goal of this task is to set up an S3 bucket, configure its access settings, upload files, manage permissions, and ensure security best practices are followed. This process is essential for applications that require reliable cloud storage or public content hosting.

**Tools and Technologies Used**

Cloud Provider: Amazon Web Services (AWS)

Service: AWS S3 (Simple Storage Service)

Platform: AWS Management Console

Additional Tools: GitHub (for documentation)

**Implementation Steps**

1. Sign in to AWS Console

Log into your AWS account via https://aws.amazon.com/. Make sure your account has the necessary permissions to access and manage S3.

2. Navigate to S3

Search for "S3" in the AWS console and open the service dashboard. This is where you can manage all your storage buckets and objects.

3. Create an S3 Bucket

Click “Create bucket” and fill in the required details:

Bucket Name: Must be globally unique

Region: Choose the nearest AWS region

Block Public Access: Enable or disable based on your need (for public files, uncheck “Block all public access”)

Leave default options for versioning and encryption for now (can be enabled later)
Click “Create bucket” to proceed.


4. Upload Files

Open the newly created bucket

Click “Upload”, select files from your local system, and click “Upload” again

Uploaded files will appear in the object list


5. Manage Access and Permissions

To make an object public, select it → click Actions → Make public

Alternatively, go to Permissions → Add a Bucket Policy to control public or restricted access

IAM roles can also be used for fine-grained access control


6. Access Objects

After upload, select a file and copy its Object URL

Paste it in a browser (if permissions allow) to view/download the file


**OUTPUT**

**STEP 1:** Create Bucket 
<img width="1361" height="639" alt="Image" src="https://github.com/user-attachments/assets/f040252b-9188-4065-9b28-cb49cd5dc98a" />

**STEP 2:** Bucket created successfully 

<img width="1362" height="602" alt="Image" src="https://github.com/user-attachments/assets/571dae79-2aed-4271-9b5e-9714d2579458" />

**STEP 3:** object creation 

<img width="1358" height="608" alt="Image" src="https://github.com/user-attachments/assets/911a13fe-e6b6-47f1-b00e-3466b7c53c3b" />

**STEP 4:** files upload 

<img width="1351" height="611" alt="Image" src="https://github.com/user-attachments/assets/b0abb0ac-82de-4a18-be5b-70b8aba17a00" />

**STEP 5:** permission apply 

<img width="1365" height="626" alt="Image" src="https://github.com/user-attachments/assets/f9837b08-13a5-4843-8933-ec5b105ebbeb" />

**STEP 6:** URL for WEBSITE HOSTING 

<img width="1363" height="715" alt="Image" src="https://github.com/user-attachments/assets/c2bbd889-dfec-4f36-965e-29cbc09d0dba" />

**STEP 7:** Static Website Hosting

<img width="1365" height="718" alt="Image" src="https://github.com/user-attachments/assets/56705e62-d68e-4f01-a73c-6f72adeb7b5b" />
