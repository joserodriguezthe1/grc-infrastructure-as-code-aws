AWS GRC CloudFormation Project

Overview

This project demonstrates Infrastructure as Code (IaC) using AWS CloudFormation to deploy a secure EC2 instance aligned with Governance, Risk, and Compliance (GRC) principles.

---

## 🧱 Architecture
- EC2 (t2.micro - Free Tier)
- IAM Role (SSM access)
- Security Group
- Encrypted EBS Volume

---

## 🔐 GRC Controls Implemented
- ✅ Encryption at rest (EBS)
- ✅ IAM role (no hardcoded credentials)
- ✅ Least privilege network access
- ✅ Resource tagging for governance
- ✅ Secure access via Systems Manager (no SSH required)

---

## 📸 Screenshots

### 1. CloudFormation Stack
![CloudFormation](screenshots/cloudformation-stack.png)

### 2. Resources Created
![Resources](screenshots/resources-created.png)

### 3. EC2 Instance Running
![EC2](screenshots/ec2-running.png)

### 4. Secure Access via SSM ⭐
![SSM](screenshots/ssm-session.png)

### 5. Encrypted Volume
![Encryption](screenshots/encryption.png)

### 6. IAM Role
![IAM](screenshots/iam-role.png)

### 7. Security Group (Restricted Access)
![Security](screenshots/security-group.png)

### 8. Resource Tagging
![Tags](screenshots/tags.png)

---

## ⚙️ Deployment Steps
1. Upload template.yaml to AWS CloudFormation
2. Provide EC2 Key Pair
3. Launch stack
4. Validate security controls

---

## 💡 Key Takeaways
This project demonstrates how security and compliance can be embedded directly into infrastructure using Infrastructure as Code (IaC).

---

## 👤 Author
Jose Rodriguez
