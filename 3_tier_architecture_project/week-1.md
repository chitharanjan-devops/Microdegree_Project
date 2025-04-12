## 📚 Week 1: VPC & Networking Setup

✅ Objective: Set up a secure, scalable, multi-AZ VPC architecture.

Tasks:

Create a custom VPC with:

2 Public Subnets (across 2 AZs)

2 Private Subnets 

---

Set up:

Internet Gateway (IGW)

Route Tables (public + private)

NAT Gateway (for private instances to access the internet)

Test: Launch a basic EC2 in each subnet with proper connectivity.

🔧 Tools:

AWS VPC, Subnets, IGW, NAT, Route Tables, EC2

---

### Architecture
![My Image](./Images/3-tier-week-1.jpg)