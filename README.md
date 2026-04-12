# 🌐 Internet Security Flow Analysis

> A beginner cybersecurity project focused on understanding how internet systems work, where security risks emerge, and how defensive controls are applied.

---

## 📌 Project Overview

This project analyzes how internet communication works and identifies where cybersecurity risks can occur across that process.

Instead of treating networking and security as separate topics, this project connects them into a single real-world flow—from a user accessing a website to how systems respond—while highlighting where attacks can happen and how they are mitigated.

---

## 🔄 Internet Communication Flow

1. User enters a domain name  
2. DNS resolves domain → IP address  
3. Browser sends request to server  
4. Request travels across networks  
5. Server processes the request  
6. Server sends response  
7. Browser displays the result  

---

## 🔍 Visual Flow Overview

User → DNS → Server → Response
↓
Potential Attack Points
↓
Defensive Controls (Firewall, Monitoring)

---

## ⚠️ Key Security Risks

- **DNS Spoofing** → Redirecting users to malicious systems  
- **Data Exposure** → Unsecured communication (lack of encryption)  
- **Open Ports** → Unauthorized access to exposed services  
- **Injection Attacks** → Malicious input manipulating system behavior  

---

## 🛡️ Defensive Measures

- **Firewall** → Controls incoming and outgoing traffic  
- **VPN / Encryption** → Protects communication channels  
- **Monitoring & Logging** → Detects suspicious activity  
- **Secure Configuration** → Reduces unnecessary exposure  
- **Input Validation** → Prevents malicious data injection  

---

## 🔐 Core Security Principle

**CIA Triad:**
- **Confidentiality** → Protect sensitive data  
- **Integrity** → Ensure data is accurate and not altered  
- **Availability** → Maintain system accessibility  

---

## 🌍 Real-World Scenario

**Phishing Attack via DNS Manipulation**

A user attempts to access their banking website using the correct domain.  
However, DNS manipulation redirects the request to a malicious server.

The fake website appears identical to the real one, and the user unknowingly enters their credentials.

These credentials are captured by the attacker.

### What went wrong:
- DNS trust was compromised  
- No verification mechanism was used  
- The user could not detect the fake system  

### How it could be reduced:
- Secure DNS practices  
- HTTPS verification  
- Multi-Factor Authentication (MFA)  
- User awareness  

---

## 📄 Project Document

Full detailed analysis:  
👉 [Download PDF](./Internet-Security-Flow-Analysis-Siam.pdf.pdf)

---

## 🎯 Learning Outcome

This project demonstrates how foundational networking concepts connect directly to real-world cybersecurity risks.

It reflects the ability to:
- Understand system-level communication  
- Identify potential attack surfaces  
- Apply defensive thinking  
- Analyze security from both attacker and defender perspectives  

---

## 👤 Author

**MD Siam Babon**  
Aspiring Cybersecurity Analyst  
Focused on Cloud Security, IAM, and practical cybersecurity skill development
