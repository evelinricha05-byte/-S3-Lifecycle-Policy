# Implementing an Amazon S3 Lifecycle Policy

## 📌 Overview
Amazon S3 Lifecycle Policies help automatically manage objects in an S3 bucket by transitioning them to lower-cost storage classes or deleting them after a specified time.  
This project demonstrates how to configure and apply an S3 Lifecycle Policy to optimize storage cost and data management.

---

## 🎯 Objectives
- Create an Amazon S3 bucket
- Upload objects to the bucket
- Configure lifecycle rules
- Transition objects to lower-cost storage
- Automatically delete expired objects

---

## 🛠️ AWS Services Used
- **Amazon S3**
- **AWS Management Console**
- **IAM (for permissions)**

---

## 🧱 Prerequisites
- AWS account
- Basic knowledge of Amazon S3
- IAM permissions to manage S3 buckets

---

## 🚀 Step-by-Step Implementation

### 1️⃣ Create an S3 Bucket
- Open **AWS Management Console**
- Navigate to **S3**
- Click **Create bucket**
- Provide a unique bucket name and region
- Keep default settings and create the bucket

---

### 2️⃣ Upload Objects
- Open the created bucket
- Click **Upload**
- Add sample files (images, documents, logs, etc.)
- Upload the objects successfully

---

### 3️⃣ Configure Lifecycle Policy
- Go to the **Management** tab in the bucket
- Click **Create lifecycle rule**
- Enter
