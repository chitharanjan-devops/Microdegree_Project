📚 Week 1: VPC & Networking Setup (Foundation Layer)

✅ Objective: Set up a secure, scalable, multi-AZ VPC architecture.

Tasks:

Create a custom VPC with:

2 Public Subnets (across 2 AZs)

4 Private Subnets (2 for app layer, 2 for DB layer)

---

Set up:

Internet Gateway (IGW)

Route Tables (public + private)

NAT Gateway (for private instances to access the internet)

Test: Launch a basic EC2 in each subnet with proper connectivity.

🔧 Tools:

AWS VPC, Subnets, IGW, NAT, Route Tables, EC2