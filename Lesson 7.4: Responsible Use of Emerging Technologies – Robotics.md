# Lesson 7.4: Responsible Use of Emerging Technologies – Robotics

## 🎯 Lesson Objectives
By the end of this lesson, students should be able to:
* **Explain** the integration of robotics with AI, IoT, and Cloud systems.
* **Identify** the societal and ethical impacts of robotic autonomy.
* **Analyze** real-world failures (Uber, Surgical robots, Bias cases).
* **Apply** Isaac Asimov’s Laws and modern professional codes to robotic design.

---

## 1. Introduction: What is Robotics?
Robotics is a multidisciplinary branch of engineering and computer science that involves the design, construction, and operation of robots. Modern robots are no longer just "dumb" mechanical arms; they are sophisticated systems that integrate **Sensors** (input), **AI/ML** (processing), and **Actuators** (output).



### The "Three Laws of Robotics" (Isaac Asimov)
1. **First Law:** A robot may not injure a human being or, through inaction, allow a human to come to harm.
2. **Second Law:** A robot must obey orders given by humans, except where such orders would conflict with the First Law.
3. **Third Law:** A robot must protect its own existence as long as such protection does not conflict with the First or Second Law.

---

## 2. Key Ethical Issues in Robotics

### 2.1 Safety and Physical Harm
Safety is the most critical professional duty in robotics. A failure in code can lead to physical injury or death.

**Case Study: Uber Self-Driving Fatality (Arizona, 2018)**
* **The Failure:** The system detected the pedestrian 5.6 seconds before impact but toggled between classifying her as a "vehicle," "bicycle," and "other object." 
* **The Result:** The system failed to trigger the emergency brakes because it was programmed to ignore "false positives" to ensure a smooth ride.
* **Professional Lesson:** Safety-critical systems must prioritize **Collision Avoidance** over "user comfort."

---

### 2.2 Privacy and Domestic Surveillance
Robots in private spaces (homes, offices) act as mobile IoT sensors.

**Case Study: Robot Vacuum Photo Leak (2021)**
* **The Incident:** Development versions of the iRobot Roomba captured images—including a woman on a toilet—which were later shared by human contractors on social media.
* **Ethical Issue:** Lack of **Informed Consent**. Users often do not realize that "mapping" their home involves sending raw images to the cloud for AI training.

---

### 2.3 Accountability and Liability: The "Black Box" Problem
When a robot malfunctions, the chain of liability is often obscured by complex AI logic.

**Case Study: Da Vinci Surgical Robot Malfunctions**
* **The Incident:** Multiple lawsuits have been filed following uncontrolled movements and accidental burns during robotic-assisted surgeries.
* **The Dilemma:** Is the fault with the **Surgeon** (operator error), the **Programmer** (software bug), or the **Manufacturer** (hardware failure)?
* **Professional Duty:** Implementing **Explainable AI (XAI)** and detailed **Black Box recorders** for every robotic movement is essential for accountability.

---

### 2.4 Bias and Racial Discrimination in Sensors
Robots often "see" the world through sensors trained on limited datasets, leading to systemic exclusion.



**Case Study: The "Racist" Soap Dispenser (2015-2017)**
* **The Incident:** Infrared sensors in automated soap dispensers failed to detect hands with darker skin tones because the sensors were tuned to reflect light off lighter surfaces.
* **Statistical Context:** Research by MIT and Stanford (Gender Shades project) found that while AI-powered vision systems have an error rate of **0.8% for light-skinned men**, the error rate jumps to **34.7% for dark-skinned women**.
* **Lesson:** Diversity in testing is a technical requirement, not just a social one.

---

### 2.5 Autonomy and Lethal Robotics
The most controversial area of robotics involves **Lethal Autonomous Weapons Systems (LAWS)**.

**Case Study: SGR-A1 Sentry Robots (South Korea)**
* **The System:** Stationed at the DMZ, these robots can detect, track, and fire upon targets autonomously.
* **Ethical Concern:** The "Moral Buffer"—if a robot makes a mistake and kills an innocent civilian, no human feels the direct moral weight of pulling the trigger.

---

## 3. Summary of Ethical Risks & Professional Response

| Risk | Case Example | Professional Response |
| :--- | :--- | :--- |
| **Physical Harm** | Uber Fatality | Fail-safe defaults and redundant sensors. |
| **Privacy Breach**| Roomba Photo Leak | Data anonymization and local edge processing. |
| **Bias** | Soap Dispenser | Inclusive datasets and sensor calibration for all users. |
| **Lack of Transparency** | Tesla Autopilot | Clear marketing and "Explainable AI" logs. |

---

## 4. Responsible Practices for Robotics Practitioners
1.  **Safety-First Coding:** Use formal verification methods to ensure robot logic cannot enter a "harmful state."
2.  **Diverse Testing:** Test sensors and algorithms across different races, ages, and environments.
3.  **Human-in-the-Loop:** For critical decisions (Medical, Military, Legal), a human must always provide final authorization.
4.  **Transparency:** Clearly communicate the limitations of a robot (e.g., distinguishing between "Assisted Driving" and "Self-Driving").

---

## 🗣️ Discussion & Activity

### Discussion Questions
1. If a caregiver robot in a nursing home accidentally drops a patient, should the **software engineer** be held liable for criminal negligence?
2. Asimo’s first law says a robot cannot allow a human to come to harm. Should a robot be allowed to **lie** to a human to prevent them from feeling emotional pain?

### Group Activity: The "Robot Bill of Rights" (10 mins)
**Scenario:** You are designing a security robot for a Kenyan shopping mall.
* **Task:** Draft **three ethical rules** for the robot to ensure it doesn't racially profile shoppers or violate their privacy while patrolling.

---
© 2026 ICT Ethics & Law Module. Distributed under the MIT License.