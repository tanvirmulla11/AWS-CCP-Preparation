
# 🌐 Day 17: AWS VPC & Networking – DevOps Learning Journey

Welcome to **Day 17** of my Cloud & DevOps learning journey!  
Today’s focus was on understanding the **networking backbone of AWS** — Virtual Private Cloud (VPC) and all the components that make secure and scalable cloud networking possible.

---

## 📚 Topics Covered

### ✅ 171. VPC Overview
- Introduction to AWS Virtual Private Cloud.
- Custom-defined virtual networks within AWS.

### ✅ 172. IP Addresses in AWS
- Public vs Private IPs.
- Elastic IP concepts.

### ✅ 173–174. VPC, Subnet, Internet Gateway & NAT Gateways
- How routing works inside AWS.
- Internet access: IGW for public subnets, NAT Gateways for private.
- 💻 Hands-on with VPC creation and subnet setup.

### ✅ 175. Security Groups & NACL
- Security Groups = instance-level firewalls.
- NACLs = subnet-level stateless firewalls.
- Key differences and use cases.

### ✅ 176. VPC Flow Logs & VPC Peering
- Flow Logs: capture network traffic.
- Peering: connect VPCs privately across accounts/regions.

### ✅ 177. VPC Endpoints – Interface & Gateway (S3 & DynamoDB)
- Interface endpoints use ENIs for private access.
- Gateway endpoints use route tables.

### ✅ 178–180. PrivateLink, Direct Connect, VPN
- PrivateLink for exposing services privately.
- Direct Connect = private line to AWS.
- VPN types: Site-to-Site and Client VPN.

### ✅ 181. Transit Gateway
- Hub-and-spoke model to simplify network peering and routing.

### ✅ 182. VPC Summary & Quiz
- Review of all networking elements with summary and quiz.

---

## 🚀 Key Learnings

- VPC is fundamental to secure, private cloud architecture.
- Designing scalable and segmented networks requires proper planning of subnets, routing tables, gateways, and access control.
- VPC Peering and Transit Gateway are key for multi-account networking.

---

## 📌 Notes

- Always enable **Flow Logs** to monitor traffic.
- Use **NAT Gateways** for outbound internet access in private subnets.
- Prefer **VPC Endpoints** to reduce latency and improve security for S3/DynamoDB access.

---

> 🛠️ Practiced hands-on VPC setup with subnets, route tables, NAT/IGW, and created secure networking paths in AWS.

Stay tuned for **Day 18**: Load Balancing & Auto Scaling!

