# 📅 Day 21: Advanced Identity - AWS IAM, STS, Cognito & More

Welcome to Day 21 of the **#100DaysOfCloud** journey!  
Today’s focus was on deepening our understanding of AWS identity services beyond IAM, including **STS**, **Cognito**, **Directory Services**, and the **IAM Identity Center**.

---

## 🎯 Topics Covered

### 🔐 234. Security Token Service (STS) Overview – *2 min*
- Grants **temporary, limited-privilege credentials**.
- Ideal for cross-account access or federated user authentication.
- Supports AssumeRole, GetSessionToken, AssumeRoleWithSAML.

---

### 👥 235. Amazon Cognito Overview – *1 min*
- Provides **user sign-up, sign-in**, and access control to web/mobile apps.
- Integrates with **social identity providers** (Google, Facebook, etc.).
- Uses **User Pools** (authentication) and **Identity Pools** (authorization).

---

### 🗂 236. Directory Services Overview – *3 min*
- Helps connect AWS resources with **existing on-premises Active Directory**.
- Supports **Microsoft AD**, **Simple AD**, and **AD Connector**.
- Useful for domain joining EC2 instances and centralized user authentication.

---

### 🧑‍💼 237. IAM Identity Center (formerly AWS SSO) – *2 min*
- Enables **centralized access management** for multiple AWS accounts.
- Integrates with Azure AD, Okta, and other IdPs.
- Replaces AWS SSO with improved identity federation support.

---

### 📚 238. Summary – *1 min*
- Quick recap of advanced identity services:
  - STS = temporary credentials
  - Cognito = user authentication for apps
  - Directory Services = AD integration
  - IAM Identity Center = multi-account access management

---

### 📝 Quiz 18: Advanced Identity Quiz
Tested understanding of:
- When to use STS vs. Cognito
- Role of Identity Pools/User Pools
- Use cases for Directory Services and Identity Center

---

## ✅ Key Takeaways

- 🔐 Use **STS** for federated, temporary access scenarios.
- 📲 Use **Cognito** for user identity in applications.
- 🧩 Use **Directory Services** when integrating with **Active Directory**.
- 🏢 Use **IAM Identity Center** for managing access across multiple AWS accounts from a **single pane of glass**.

---

### 🔗 Resources

- [AWS STS Docs](https://docs.aws.amazon.com/STS/latest/APIReference/Welcome.html)  
- [Amazon Cognito](https://aws.amazon.com/cognito/)  
- [AWS Directory Service](https://aws.amazon.com/directory-service/)  
- [IAM Identity Center](https://docs.aws.amazon.com/singlesignon/latest/userguide/what-is.html)

---

🔁 Stay consistent, keep learning, and build strong identity foundations in AWS Cloud!

