# Lesson 4.8: Plagiarism in AI-Assisted Coding

## 🎯 Lesson Objectives
* **Define** plagiarism as it applies to modern programming.
* **Understand** how AI tools (Copilot, ChatGPT) can unintentionally generate plagiarized content.
* **Differentiate** between *Acceptable Use*, *Fair Use*, and *Plagiarism*.
* **Apply** the ACM/IEEE Code of Ethics to maintain professional integrity.

---

## 1. The New Face of Plagiarism
In the past, plagiarism was simple: copying a friend's disk or downloading a script from a forum. Today, **AI-Assisted Plagiarism** occurs when a developer uses generative AI to produce code and submits it as their own original work without disclosure.

> **Key Conflict:** AI doesn't "invent" code; it predicts it based on existing human-written datasets. If you present AI output as your own creative logic, you are taking credit for a "collective" work you didn't actually author.

---

## 2. How AI Tools Lead to Plagiarism
AI models are trained on billions of lines of code. When you give a specific prompt, the AI may provide a **verbatim** or **near-identical** copy of a function from a public repository.



### The Responsibility Shift
Unlike human authors, AI does not provide citations. It is the **user's responsibility** to:
1.  Verify the originality of the code.
2.  Disclose the use of AI assistance.
3.  Ensure the code doesn't violate the original creator's license (e.g., GPL, MIT).

---

## 3. Real-Life Case: Student Submissions (2023-2025)
Universities globally and in Kenya (e.g., Strathmore, UoN) have updated their academic integrity policies.
* **The Flagging:** Tools like **MOSS (Measure of Software Similarity)** and **Codequiry** now have "AI-Detection" layers.
* **The Lesson:** Even if the AI "hallucinates" a slightly different variable name, the underlying logic (the "fingerprint") often matches existing public code, leading to plagiarism charges.

---

## 4. Plagiarism vs. Acceptable AI Use

| Activity | Status | Ethical Justification |
| :--- | :--- | :--- |
| **Ideation** | ❌ Acceptable | Using AI to explain a concept or suggest a data structure. |
| **Debugging** | ❌ Acceptable | Asking AI to find a syntax error in code *you* wrote. |
| **Verbatim Copying** | ✅ Plagiarism | Pasting AI code directly into a project and claiming you wrote it. |
| **Logic Theft** | ✅ Plagiarism | Using AI to "paraphrase" a complex algorithm to hide its source. |

---

## 5. Professional Ethics: The ACM Code
The **ACM Code of Ethics (Section 1.3)** states: *"Be honest and trustworthy."*
Presenting AI-generated code as your own work is a violation of this principle because:
* **Honesty:** It is a false claim of authorship.
* **Trust:** It prevents peers or employers from knowing the true source of the code’s logic or potential vulnerabilities.

---

## 6. How to Avoid Plagiarism in Your Practice
1.  **Acknowledge the Tool:** Add a comment header to your files:
    ```python
    # Generated with assistance from GitHub Copilot
    # Logic based on OpenAI GPT-4 suggestions
    ```
2.  **Use AI for "Skeletons," not "Bodies":** Use AI to generate boilerplate (like a basic HTML structure) but write the core business logic yourself.
3.  **Run Scanners:** Before submitting, use **Copyleaks** or **Codequiry** to see if your AI-generated code matches known repositories.
4.  **Understand the "Why":** If you can't explain how the AI's code works, you shouldn't be using it.

---

## 🗣️ Discussion & Activities

### Discussion Prompt
*If a developer uses AI to generate 90% of an app's code but spends 10 hours debugging and refining it, who is the "author"? Should they be allowed to register the copyright in Kenya?*

### Group Activity: The Transparency Audit (10 mins)
**Scenario:** Your team is using AI to build a mobile banking module.
1.  Design a **Documentation Standard** (e.g., a specific comment format) that shows which parts are AI-generated vs. Human-written.
2.  Draft a 2-sentence **Disclosure Statement** you would include in your final project report.

---
© 2026 ICT Ethics & Law Module. Distributed under the MIT License.