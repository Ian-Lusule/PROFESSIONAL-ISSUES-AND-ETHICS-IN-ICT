# Lesson 4.6: Software Piracy in AI-Assisted Coding

## 🎯 Lesson Objectives
By the end of this lesson, you should be able to:
* **Explain** software piracy within the context of AI-assisted coding tools.
* **Identify** the legal risks when AI models reproduce copyrighted code snippets.
* **Analyze** the *GitHub Copilot (2022)* class-action lawsuit.
* **Apply** best practices for the ethical use of AI coding assistants.

---

## 1. Introduction: The AI Frontier
AI-powered tools like **GitHub Copilot**, **ChatGPT**, and **Claude** are trained on billions of lines of public code. While they boost productivity, they create a new legal "grey area": 
* Does AI "learn" like a human, or does it "copy" like a machine?
* If AI outputs a function identical to a proprietary library, is that **Software Piracy**?

---

## 2. Defining Piracy in the AI Context
In the traditional sense, software piracy is the unauthorized copying of an executable. In the AI era, it evolves into **unauthorized reproduction of source code without attribution**.

### Key Risks:
* **The "Black Box" Problem:** AI models don't always disclose the source of their suggestions. You might unknowingly paste GPL-licensed code into a closed-source commercial project.
* **License Laundering:** Using AI to rewrite copyrighted code just enough to bypass detection but keeping the original logic/structure without a license.
* **Lack of Attribution:** Most open-source licenses (MIT, Apache, GPL) require you to credit the original author. AI tools often omit this, leading to technical license violations.



---

## 3. Real-Life Case Study: GitHub Copilot Lawsuit (2022)
**Case:** *Doe v. GitHub, Microsoft, and OpenAI*

### The Allegation
In 2022, developers filed a class-action lawsuit claiming that GitHub Copilot was trained on public repositories but was outputting "verbatim" (exact) copies of code without:
1. Providing attribution to the original authors.
2. Including the required copyright notices/licenses.

### The Defense
Microsoft and OpenAI argued that training AI on public data falls under **Fair Use**. They compared the AI's "training" to a human student reading a textbook to learn how to solve a math problem.

### The Kenyan Perspective (2025/2026 Update)
The **Kenya Copyright Tribunal** and **KECOBO** have recently affirmed that copyright protection in Kenya applies only to works with **demonstrable human creative input**. 
* **Purely AI-generated code:** May not be eligible for copyright protection in Kenya.
* **AI-assisted code:** If a human developer directs, edits, and refines the AI output, the final product is likely protected under the human's authorship.

---

## 4. Ethical & Legal Comparison

| Feature | Traditional Software Piracy | AI-Assisted "Piracy" |
| :--- | :--- | :--- |
| **Intent** | Usually intentional (using a "crack"). | Often unintentional (blind copy-pasting). |
| **Source** | Warez sites, torrents, unauthorized keys. | Legitimate coding assistants (Copilot, ChatGPT). |
| **Liability** | The person installing the pirated software. | Both the developer and potentially the AI provider. |
| **Detection** | License keys, activation checks. | Code similarity scanners (Snyk, Black Duck). |

---

## 5. Best Practices for ICT Professionals
To ensure you aren't committing "AI Piracy," follow these professional standards:

1. **Keep a Human in the Loop:** Never accept an AI suggestion without reading and understanding it. 
2. **Use License Filters:** Enable "Filter suggestions matching public code" in your GitHub Copilot settings.
3. **Scan Your Code:** Use SAST (Static Analysis Security Testing) tools and license compliance scanners before deploying production code.
4. **Document AI Use:** Maintain a record of which parts of your project were AI-generated. This is vital for future copyright registration in Kenya.
5. **Prompt Ethically:** Avoid asking AI to "rewrite [X] proprietary library" or "copy the logic from [Y] competitor's app."

---

## 🗣️ Discussion & Activities

### Discussion Prompts
* If an AI reproduces a 5-line "Hello World" function, is that piracy? What if it reproduces a 500-line encryption algorithm? Where is the line?
* Who should be held responsible if an AI tool suggests code that contains a security vulnerability—the AI company or the developer who used it?

### Group Activity (10 mins)
**The "Audit" Challenge:**
Imagine your team is using ChatGPT to build a login system for a bank. List **three verification steps** you would take to ensure the code you've generated doesn't violate any open-source licenses or include "pirated" snippets from existing libraries.

---
© 2026 ICT Ethics & Law Module. Distributed under the MIT License.