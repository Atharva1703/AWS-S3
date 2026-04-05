# AWS-S3
In this project, I worked with Amazon S3 to understand storage management, access control, and hosting capabilities in AWS. I created an S3 bucket and configured permissions by disabling block public access and enabling ACLs to make specific objects publicly accessible.

I implemented object-level access control by uploading files and making them public using ACL settings, allowing external access to selected resources. To enhance data protection, I enabled versioning, which allowed me to track multiple versions of objects and recover deleted files by removing delete markers.

Additionally, I configured static website hosting on the S3 bucket by enabling the feature and uploading index.html and error.html files. This allowed the bucket to function as a simple web server, serving web content over the internet.

Finally, I validated the setup by accessing public files, testing version recovery, and verifying the hosted website functionality, demonstrating practical knowledge of cloud storage, security, and hosting in AWS.

# ☁️AWS S3 Bucket Configuration, Versioning & Static Website Hosting
# 📌 Project Overview

This project demonstrates how to configure and manage cloud storage using Amazon S3, including public access control, versioning for data recovery, and hosting a static website.

# 🎯Objectives
Create and configure an S3 bucket
Manage public access and permissions using ACL
Implement versioning for data protection
Host a static website using S3

# 🛠️Services Used
Amazon S3

# ⚙️Implementation Steps
1️⃣ Create S3 Bucket
Created a new S3 bucket
Configured permissions by disabling Block Public Access
Enabled ACL (Access Control List) settings

📸 Add Screenshot Here (Bucket Creation)

2️⃣ Manage Object Access
Uploaded files to the bucket
Made selected objects public using ACL settings
Verified public access via object URL

📸 Add Screenshot Here (Public Object Access)

3️⃣ Enable Versioning
Enabled versioning in bucket properties
Uploaded multiple versions of files
Deleted objects and restored them by removing delete markers

📸 Add Screenshot Here (Versioning & Recovery)

4️⃣ Static Website Hosting
Enabled static website hosting
Uploaded index.html and error.html files
Configured index and error documents
Accessed the hosted website via S3 endpoint

📸 Add Screenshot Here (Website Hosting Output)

# ✅Key Outcomes
Implemented secure and controlled object access
Gained hands-on experience with S3 versioning and recovery
Successfully hosted a static website on S3
Understood real-world cloud storage and hosting concepts

#🚀Conclusion

This project showcases practical experience with AWS S3, including storage management, access control, versioning, and static website hosting, which are essential skills for cloud and DevOps roles.
