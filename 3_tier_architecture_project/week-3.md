🚀 **AWS Mega Project – Week 4 Task**

📌 **What You’ll Do**:
✅ Register domain on **GoDaddy**  
✅ Point it to **Route53** using custom name servers  
✅ Set up **CloudFront** for caching and distribution  
✅ Configure **Application Load Balancer** in public subnets  
✅ Launch **EC2 instances** (Nginx) in private subnets via **Auto Scaling Group**  
✅ Create **Target Group** and attach EC2s  
✅ ALB ➜ Private EC2 (Nginx) = Working Website!

🔒 **Security Tips**:
- Public subnet ➜ Only ALB  
- Private subnet ➜ Only EC2  
- No direct access to EC2s from internet!

🔄 **Auto Scaling**:
- Configure ASG for EC2s so traffic surges are handled easily.

Refer to the attached architecture diagram

## Architecture
![My Image](./Images/3-tier-week-4.jpg)