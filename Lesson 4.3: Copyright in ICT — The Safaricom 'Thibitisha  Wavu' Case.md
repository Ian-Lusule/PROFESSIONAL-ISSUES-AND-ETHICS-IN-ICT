---
title: "Lesson 4.3: Copyright in ICT — The Safaricom 'Thibitisha / Wavu' Case"
date: 2026-01-20
category: Intellectual Property
tags: [Copyright, KECOBO, Software Law, Safaricom, ICT Ethics]
---

# Lesson 4.3: Copyright in ICT

## 🎯 Learning Objectives
By the end of this lesson, you should be able to:
* **Define** copyright and its role in protecting digital intellectual work.
* **Analyze** how the Kenyan legal system treats software as "Literary Work."
* **Discuss** the Safaricom vs. Solut Technology case as a cautionary study for developers.
* **Understand** the registration process with the **Kenya Copyright Board (KECOBO)**.

---

## 1. What is Copyright?
Copyright is a legal right granted to creators that provides exclusive control over the reproduction and distribution of their original works.

### Key Characteristics:
* **Automatic Protection:** In Kenya, copyright exists the moment you "fix" your work in a tangible form (e.g., saving code to a disk or writing it in a notebook).
* **Economic Rights:** Allows you to earn from your work (selling, leasing, or licensing).
* **Moral Rights:** Protects your reputation as the author (e.g., the right to be credited).

---

## 2. Copyright and Software in Kenya
Under the **Copyright Act (Cap 130)**, computer programs are classified as **Literary Works**. 

* **What is protected:** Source code, object code, user interfaces, and technical documentation.
* **Ownership:** Generally, the developer owns the code. However, if you are an employee under a **"Contract of Service,"** the copyright usually belongs to your employer unless stated otherwise.



---

## 3. Case Study: Solut Technology vs. Safaricom (Thibitisha / Wavu)
This landmark case highlights the gap between having a "good idea" and having "legal proof."

### The Dispute:
Solut Technology pitched an app called **"Wavu"** to Safaricom via their *Zindua Cafe* portal. After Safaricom rejected the pitch, they launched a similar identity-verification service called **"Thibitisha."**

### The Court's Ruling:
The court dismissed Solut's claim because:
1.  **Lack of Fixation:** Solut submitted a "concept note" but could not provide the **source code** (the actual expression).
2.  **No Proof of Ownership:** Solut had not registered the code with KECOBO, making it difficult to prove *what* was created and *when*.
3.  **Independent Creation:** Safaricom proved their team developed the app independently.

> **Moral of the Story:** Copyright protects **expressions**, not **ideas**. You cannot stop someone from building a "taxi app," but you can stop them from stealing *your specific code* for a taxi app.

---

## 4. The Role of KECOBO
The **Kenya Copyright Board (KECOBO)** is the state agency that manages copyright law.

* **National Rights Registry (NRR):** An online portal where you can voluntarily register your software.
* **Evidential Weight:** While registration is not mandatory, a **KECOBO Certificate** is *prima facie* evidence in court—it puts the burden of proof on the other party to show you *don't* own the work.

### Steps to Register Your Software:
1.  Access the **NRR Portal** (nrr.copyright.go.ke) via eCitizen.
2.  Upload **Source Code Excerpts** (typically the first and last 25 pages).
3.  Provide a detailed software description.
4.  Pay the prescribed fee (approx. **Ksh 1,000**).

---

## 5. Duration of Protection
| Work Type | Duration in Kenya |
| :--- | :--- |
| **Software / Literary** | Author's life + 50 years |
| **Audio-Visual / Photos** | 50 years from publication |
| **Sound Recordings** | 50 years from recording date |

---

## 📝 Activity: The "Safety Checklist"
Imagine you have just finished a new health-tracking app. To avoid a "Solut vs. Safaricom" situation, follow these five steps:
1.  **Version Control:** Use Git (GitHub/GitLab) to maintain a timestamped history of your code.
2.  **NDA:** Never pitch without a signed Non-Disclosure Agreement.
3.  **Register:** Submit your work to the KECOBO NRR portal.
4.  **License:** Clearly state the terms of use in your `LICENSE.txt` file.
5.  **Audit Logs:** Keep records of all meetings and communications with potential investors.

---

## 🗣️ Discussion Questions
* How does the "Idea-Expression Dichotomy" impact innovation?
* Why is a "Concept Note" usually insufficient for a copyright claim?