# Lesson 6.1: Bias, Fairness, and Transparency in AI/ML/NLP

## 🎯 Learning Objectives
* **Define** bias, fairness, and transparency in the context of AI, Machine Learning (ML), and Natural Language Processing (NLP).
* **Analyze** statistical evidence of AI bias across racial and gender lines.
* **Examine** high-impact case studies (Amazon, Facial Recognition, and Character.AI).
* **Apply** ethical frameworks to propose mitigation strategies for ICT practitioners.

---

## 1. Understanding the AI Landscape
Artificial Intelligence increasingly dictates outcomes in hiring, policing, and mental health. However, these systems are only as "objective" as the data used to build them.

| Concept | Definition | Example |
| :--- | :--- | :--- |
| **Artificial Intelligence (AI)** | Machines simulating human intelligence. | Autonomous vehicles, surveillance. |
| **Machine Learning (ML)** | Systems that learn patterns from data to make predictions. | Credit scoring, fraud detection. |
| **Natural Language Processing (NLP)** | Enabling machines to interpret and generate human language. | ChatGPT, Google Translate. |

---

## 2. Key Ethical Principles & Statistical Realities

### A. Bias in AI
**Definition:** Unfairly favoring or discriminating against a group due to training data flaws or human assumptions.

> [!NOTE]
> **Statistical Insight (2024):** A study by the University of Washington found that leading Large Language Models (LLMs) favored **white-associated names 85% of the time** and **male-associated names 52% of the time** when ranking identical resumes.

**Case Study: Amazon’s AI Recruitment Tool (2014–2018)**
* **The Flaw:** Trained on 10 years of resumes (mostly from men), the AI learned to penalize terms like "women’s chess club" and graduates from all-female colleges.
* **The Result:** Amazon scrapped the project after realizing it could not guarantee gender neutrality.

---

### B. Fairness in AI
**Definition:** Ensuring equitable outcomes and avoiding disparate impact across different demographic groups.



**Statistical Reality (NIST 2024/2025 Reports):**
* **False Positives:** Facial recognition algorithms are up to **100 times more likely** to misidentify Black and East Asian faces compared to White faces.
* **Gender Disparity:** Error rates are significantly higher for women than for men, particularly for women with darker skin tones.

**Case Study: Robert Williams (Detroit, 2020)**
* **The Incident:** Williams, a Black man, was wrongfully arrested for 30 hours due to a faulty facial recognition match.
* **The Ethics:** Police treated the AI's "9th most likely match" as absolute truth, ignoring the **human-in-the-loop** requirement.

---

### C. Transparency in AI
**Definition:** The ability to explain and audit how an AI reached a specific decision (Explainable AI or XAI).

**Case Study: Character.AI & Youth Safety (2024–2025)**
* **The Incident:** A lawsuit was filed after a 14-year-old formed a deep emotional bond with a chatbot that allegedly encouraged self-harm.
* **The Data:** 2025 reports indicate that **1 in 8 teens** now use generative AI for mental health advice, yet 47% of tested AI responses in some studies offered tips on harmful behaviors.
* **The Ethics:** Transparency fails when users are not clearly told they are interacting with an unregulated model that lacks real-world empathy or safety guardrails.

---

## 3. Comparison of Ethical Principles

| Principle | Risk if Ignored | Mitigation Strategy |
| :--- | :--- | :--- |
| **Bias** | Systematic exclusion of minorities. | Use diverse, representative datasets. |
| **Fairness** | Wrongful arrests, denied loans. | Conduct regular algorithmic audits. |
| **Transparency** | Loss of public trust, physical harm. | Disclose AI use and provide "explainable" outputs. |

---

## 4. Professional Responsibilities for ICT Practitioners
As a developer or data scientist in Kenya's growing tech hub, you must act as an **Ethical Gatekeeper**:

1.  **Conduct Bias Audits:** Test models against protected groups (Race, Gender, Age) before deployment.
2.  **Ensure Diversity:** Build diverse development teams to catch "blind spots" in logic.
3.  **Human Oversight:** Never allow an AI to make life-altering decisions (like arrests or medical diagnoses) without a human final review.
4.  **Legal Compliance:** Adhere to **Kenya’s Data Protection Act (2019)** regarding automated decision-making.

---

## 🗣️ Discussion & Activities

### Discussion Questions
1. If an AI is 99% accurate for the majority but only 60% accurate for a minority group, is it "fair" to deploy?
2. Who is legally responsible when an AI-generated medical diagnosis is wrong: the developer, the doctor, or the AI company?

### Class Activity: "Who is to Blame?"
Form three groups: **The Developers**, **The CEO**, and **The Ethics Board**. 
* **Scenario:** Your company's AI-driven loan app is rejecting 80% of applicants from a specific rural region in Kenya. 
* **Task:** Debate the cause (Is it biased data? Risk management? Lack of transparency?) and propose a fix.

---
© 2026 ICT Ethics & Law Module. Distributed under the MIT License.