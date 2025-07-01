
# 📘 Day 06 - AWS ELB & ASG (Elastic Load Balancing & Auto Scaling Groups)

This repository documents my learning and hands-on experience from **Section 7: ELB & ASG** of the AWS Cloud Practitioner course on Udemy.

## 🎯 Section Summary
Learned how to ensure **High Availability**, **Scalability**, and **Elasticity** using AWS services like:
- Elastic Load Balancers (ELB)
- Application Load Balancer (ALB)
- Auto Scaling Groups (ASG)

---

## 📚 Topics Covered

| # | Topic | Duration |
|--|------------------------------|----------|
| 65 | High Availability, Scalability, Elasticity | 6 min |
| 66 | Elastic Load Balancing (ELB) Overview | 7 min |
| 67 | Application Load Balancer (ALB) Hands-On | 9 min |
| 68 | Auto Scaling Groups (ASG) Overview | 3 min |
| 69 | Auto Scaling Groups (ASG) Hands-On | 9 min |
| 70 | Auto Scaling Groups (ASG) Strategies | 3 min |
| 71 | Section Cleanup | 1 min |
| 72 | ELB & ASG Summary | 2 min |

---

## 🛠️ Hands-On Labs

### ✅ Application Load Balancer (ALB)
- Created ALB with target groups
- Configured listener rules for HTTP traffic
- Attached EC2 instances
- Performed health checks

### ✅ Auto Scaling Groups (ASG)
- Created Launch Template
- Deployed ASG with min/max/desired capacity
- Implemented dynamic scaling policy
- Verified automatic instance scaling based on CPU usage

---

## 💡 Key Takeaways
- ELBs distribute incoming traffic across multiple targets (EC2, Lambda, etc.)
- ALBs work at Layer 7 (HTTP/HTTPS) and support path-based routing
- ASGs help maintain application availability and cost-efficiency
- ASGs can be configured with different scaling strategies (manual, scheduled, dynamic)

---

## 🧼 Cleanup
All AWS resources created in this section (ALB, ASG, EC2 instances) were terminated to avoid unwanted charges.

---

## 🚀 Next Section
Moving on to:
