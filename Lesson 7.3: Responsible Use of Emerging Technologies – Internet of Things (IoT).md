# Lesson 7.3: Responsible Use of Emerging Technologies – Internet of Things (IoT)

## 🎯 Lesson Objectives
By the end of this lesson, students should be able to:
* **Explain** the technical architecture of IoT.
* **Identify** the unique ethical and security risks of connected devices.
* **Analyze** real-world IoT failures (Nairobi CCTV leaks, Jeep hacks).
* **Recommend** responsible design and deployment practices for ICT practitioners.

---

## 1. Introduction: What is IoT?
The **Internet of Things (IoT)** refers to a network of physical objects embedded with sensors, software, and communication modules that allow them to collect and exchange data autonomously.



### Common IoT Verticals:
* **Smart Homes:** CCTV, smart locks, thermostats.
* **Industrial IoT (IIoT):** Factory automation, predictive maintenance.
* **Smart Agriculture:** Soil moisture sensors, livestock GPS trackers.
* **Smart Cities:** Traffic management, smart street lighting.

---

## 2. Key Ethical & Security Issues

### 2.1 Privacy: The "Always-On" Monitor
Privacy in IoT is compromised because devices often operate silently in the background, collecting audio, video, and biometric data without explicit user awareness.

**Case Study: Nairobi CCTV Camera Leak (2020)**
* **The Incident:** Thousands of Kenyan home and business CCTV cameras were found streaming live online because they were left with **default or no passwords**.
* **The Harm:** Private living rooms, bedrooms, and offices were indexed by foreign websites and broadcasted globally.
* **Ethical Lesson:** Secure defaults and user notification of "active recording" are professional necessities.

---

### 2.2 Security: Devices as Entry Points
IoT devices are often the "weakest link" in a network due to limited processing power and unpatched firmware.



**Case Study: Jeep Cherokee Remote Hack (2015)**
* **The Incident:** Researchers remotely hijacked a vehicle's infotainment system to control the steering, brakes, and transmission.
* **The Harm:** Direct threat to human life.
* **Professional Duty:** Security must be "baked-in" to hardware, not added as an afterthought.

---

### 2.3 Trust & Transparency: Hidden Data Flows
Transparency means the user knows **what** data is being collected and **where** it is going.

**Case Study: Smart Speaker Voice Retention (2018–2020)**
* **The Conflict:** Reports revealed that Google and Amazon stored audio recordings indefinitely and used human contractors to listen to samples for "quality control" without informing users.
* **Ethical Failure:** Violation of the "Right to be Informed" and use of **Dark Patterns** to hide privacy settings.

---

### 2.4 Data Sovereignty: Jurisdiction Risks
Data sovereignty is the principle that data is subject to the laws of the country where it is stored.

**Case Study: Kenyan Surveillance Data in China (2019–2021)**
* **The Conflict:** Footage from certain IoT-powered systems in Nairobi was found to be routed and stored on servers in China.
* **Ethical Concern:** This bypasses the **Kenya Data Protection Act (2019)** and poses a national security risk as foreign governments could potentially access the data under their own laws.

---

### 2.5 Vendor Dependency: The "Brick" Risk
If an IoT vendor shuts down their cloud server, the physical hardware becomes useless—a phenomenon known as "bricking."

**Case Study: Google and the Revolv Hub (2016)**
* **The Incident:** Google acquired Revolv and shut down its cloud service, instantly turning expensive smart home hubs into paperweights.
* **Ethical Lesson:** Developers should provide an **"Offline Mode"** or open-source the firmware if a product is reaching its end-of-life to protect consumer investment.

---

## 3. Summary of IoT Ethical Risks

| Principle | Failure Example | Professional Action |
| :--- | :--- | :--- |
| **Privacy** | Nairobi CCTV Stream | Enforce password changes on first use. |
| **Safety** | Jeep Cherokee Hack | Separate critical systems (brakes) from non-critical (WiFi). |
| **Trust** | Amazon Ring Hacking | Implement Multi-Factor Authentication (MFA) by default. |
| **Compliance** | BA GDPR Fine | Regularly audit third-party scripts and modules. |

---

## 4. Responsible Practices for ICT Practitioners
To build ethical IoT systems, follow these **"Security by Design"** rules:
1.  **Unique Default Passwords:** Never ship devices with "admin/admin."
2.  **Encryption:** Use end-to-end encryption for all data transit to the cloud.
3.  **Data Minimization:** Only collect the data necessary for the device to function.
4.  **Local Processing:** Process data on the device (Edge Computing) where possible to avoid cloud leaks.
5.  **Firmware Updates:** Build a secure, automatic update mechanism to patch vulnerabilities.

---

## 🗣️ Discussion & Activity

### Discussion Questions
1. If a smart lock fails and a home is robbed, who is responsible: the software engineer, the hardware manufacturer, or the owner?
2. Should the Kenya Government ban IoT devices that store data on servers outside of Kenya?

### Group Activity: The "Privacy Label" Challenge (10 mins)
**Scenario:** You are designing a "Smart Water Meter" for a Kenyan utility company. 
* **Task:** Create a "Nutrition Label" for the device that clearly tells the customer:
  1. What data is collected.
  2. How long it is kept.
  3. If it is shared with 3rd parties.
  4. How they can delete their data.

---
© 2026 ICT Ethics & Law Module. Distributed under the MIT License.