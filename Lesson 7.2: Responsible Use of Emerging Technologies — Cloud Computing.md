# Lesson 7.2: Responsible Use of Emerging Technologies — Cloud Computing

## 🎯 Lesson Objectives
By the end of this lesson, students should be able to:
* **Explain** cloud computing as a foundation for digital transformation.
* **Identify** ethical, legal, and professional responsibilities in cloud adoption.
* **Analyze** real-world failures (Capital One, eCitizen, Meta lawsuit) to identify risks.
* **Propose** cloud governance frameworks that prioritize data sovereignty and trust.

---

## 1. Introduction: Why Cloud Matters
Cloud computing is the backbone of the modern digital economy. From **M-PESA** transactions to **eCitizen** applications, the cloud provides the "elasticity" needed to serve millions of users simultaneously.

### The "Emerging" Nature of Cloud
While cloud tech has existed for years, it remains an **emerging technology** because of its continuous evolution into:
* **Serverless Computing:** Scaling code without managing servers.
* **Edge Computing:** Moving processing closer to the user (crucial for 5G in Kenya).
* **Cloud-Native AI:** Running LLMs (like ChatGPT) on massive distributed clusters.

---

## 2. Cloud Service & Deployment Models



### Service Models (The "Stack")
1.  **IaaS (Infrastructure):** You rent the "bricks" (servers, storage). *Example: Safaricom Cloud, AWS EC2.*
2.  **PaaS (Platform):** You get the "tools" to build apps without managing the OS. *Example: Google App Engine.*
3.  **SaaS (Software):** You use the "finished house." *Example: Microsoft 365, Gmail.*

### Deployment Models
* **Public:** Resources shared over the internet (AWS, Azure).
* **Private:** Dedicated to one organization (High security).
* **Hybrid:** A mix of both (Common in Kenyan Banks).
* **Community:** Shared by organizations with common goals (e.g., Universities).



---

## 3. Ethical Principles & Case Studies

### A. Privacy & Security: The "Misconfiguration" Trap
**Case Study: Capital One Breach (2019)**
* **What Happened:** A misconfigured Web Application Firewall (WAF) allowed a hacker to access **100 million** records.
* **Ethical Failure:** Lack of "Security by Design." The organization assumed the cloud provider (AWS) was responsible for everything, ignoring the **Shared Responsibility Model**.

### B. Trust & Availability: National Resilience
**Case Study: eCitizen DDoS Attack (Kenya, 2023)**
* **What Happened:** The "Anonymous Sudan" group launched a massive DDoS attack, taking down 5,000+ government services.
* **Ethical Issue:** When a nation moves its entire "engine" to the cloud, an outage is not just a glitch—it’s a national security crisis. 
* **Lesson:** Cloud governance must include **DDoS mitigation** and **Failover** protocols.

### C. Data Sovereignty: Where is my data?
**Case Study: Meta (Facebook) Moderators Lawsuit (Kenya, 2022-2023)**
* **The Conflict:** Kenyan content moderators sued Meta, but their data and evidence were stored in **Ireland**.
* **The Dilemma:** Does Kenyan law apply to data stored on a server in Europe? 
* **Lesson:** Professionals must ensure compliance with the **Kenya Data Protection Act (2019)**, which requires "Data Localization" for sensitive national data.

### D. Vendor Lock-in & Dependency
**Case Study: Adobe in Venezuela (2019)**
* **The Incident:** US sanctions forced Adobe to cut off cloud services to an entire country. Users lost access to their own creative work.
* **Moral Risk:** If you rely 100% on one provider, you lose your digital "self-determination."

---

## 4. Summary of Risks for ICT Professionals

| Risk | Description | Professional Duty |
| :--- | :--- | :--- |
| **Vendor Lock-in** | Hard to move data to another provider. | Design for **Interoperability** (Multi-cloud). |
| **Shadow IT** | Employees using unapproved cloud apps. | Enforce strict Cloud Governance policies. |
| **Data Residency** | Data stored in jurisdictions with weak laws. | Audit where the "Physical Server" is located. |
| **Outages** | Single point of failure. | Implement **Redundancy** across different regions. |

---

## 5. Responsible Cloud Governance Practices
To use the cloud ethically, organizations must:
1.  **Adopt a Shared Responsibility Model:** Know exactly what YOU secure vs. what the PROVIDER secures.
2.  **Encrypt Data at Rest & In Transit:** The cloud provider should never be able to read your raw data.
3.  **Implement Least Privilege Access (IAM):** Only give users access to the specific bucket or folder they need.
4.  **Regular Compliance Audits:** Check against the **Kenya Data Protection Office (ODPC)** guidelines annually.

---

## 🗣️ Discussion & Activity

### Discussion Questions
1. If Safaricom Cloud goes down for 24 hours, who should pay for the lost business: Safaricom or the business owner?
2. Is it ethical for the government to store citizen biometrics on a "Public Cloud" like AWS?

### Group Activity: "Cloud Exit Strategy" (10 mins)
**Scenario:** You are the CTO of a Kenyan startup. You currently store all user data on Google Cloud. 
* **Task:** List **three technical and legal steps** you would include in your "Exit Strategy" to ensure you don't lose your data if Google decides to triple their prices tomorrow.

---
© 2026 ICT Ethics & Law Module. Distributed under the MIT License.