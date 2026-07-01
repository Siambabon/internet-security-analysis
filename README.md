# 🌐 Internet Security Flow Analysis
## 🚧 Project Status

**Status:** ✅ Completed

**Last Updated:** July 2026

>A foundational cybersecurity project that analyzes internet communication, identifies attack surfaces, and demonstrates defensive security concepts through a real-world systems perspective.

---

## 📖 Overview

Effective cybersecurity begins with understanding how modern systems communicate, where trust exists, and how that trust can be exploited or protected.

This project examines the journey of an internet request—from the moment a user enters a website address until the server returns a response—and identifies the security risks and defensive controls involved at each stage.

Rather than treating networking and cybersecurity as separate subjects, this project connects them through a practical, real-world workflow.

---

## 🎯 Project Objectives

- Understand the lifecycle of internet communication
- Identify common attack surfaces
- Explore defensive security controls
- Apply foundational cybersecurity concepts
- Develop analytical thinking from both attacker and defender perspectives

---

## 🌍 Internet Communication Workflow

```text
User
 │
 ▼
DNS Resolution
 │
 ▼
Web Browser
 │
 ▼
Internet
 │
 ▼
Firewall
 │
 ▼
Web Server
 │
 ▼
Application
 │
 ▼
Database
 │
 ▼
Response

Each stage introduces a different trust relationship and therefore a different security risk.
```

---

## ⚠️ Security Risks Across the Workflow

| Stage | Potential Risk | Security Impact | Impact | Likelihood |
|--------|----------------|-----------------|:------:|:----------:|
| DNS | DNS Spoofing | Redirects users to malicious destinations | High | Medium |
| Network | Man-in-the-Middle (MITM) | Intercepts or modifies data in transit | High | Medium |
| Web Server | Misconfiguration | Unauthorized access | High | Medium |
| Services | Open Ports | Increased attack surface | Medium | High |
| Application | Injection Attacks | Manipulation of application logic | High | Medium |
| User | Phishing | Credential theft and account compromise | High | High |

---

## 🛡️ Defensive Security Controls

| Control | Purpose |
|----------|---------|
| Firewall | Filters unauthorized network traffic |
| HTTPS / TLS | Encrypts communication between systems |
| VPN | Protects remote network communication |
| Multi-Factor Authentication (MFA) | Strengthens identity verification |
| Monitoring & Logging | Detects suspicious activity |
| Secure Configuration | Reduces unnecessary exposure |
| Input Validation | Prevents malicious input |

---

## 🔐 Security Principles

This project demonstrates the practical importance of the **CIA Triad**, the foundation of information security.

| Principle | Objective |
|-----------|-----------|
| Confidentiality | Protect sensitive information |
| Integrity | Prevent unauthorized modification |
| Availability | Ensure systems remain accessible |

---

## 🌍 Real-World Scenario

### Phishing Through DNS Manipulation

A user attempts to access an online banking website using the correct domain name.

An attacker manipulates DNS resolution, redirecting the user to a fraudulent website that appears identical to the legitimate one. Believing the website is genuine, the user enters their login credentials, which are then captured by the attacker.

### What Failed?

- DNS trust was compromised
- The destination could not be verified
- The user unknowingly trusted a malicious website

### Mitigation

- Secure DNS implementation
- HTTPS certificate verification
- Multi-Factor Authentication (MFA)
- User security awareness

---

## 📚 Skills Demonstrated

- Networking
- Threat Analysis
- Risk Assessment
- Security Fundamentals
- Technical Documentation
- Analytical Thinking
- System Thinking
- Problem Solving

---

## 🛠️ Technologies & Concepts

- TCP/IP
- DNS
- HTTP
- HTTPS
- TLS
- Firewall
- VPN
- Markdown
- Git
- GitHub

---

## 📂 Project Resources

📄 **Detailed Project Report**

➡️ [Internet Security Flow Analysis (PDF)](./Internet-Security-Flow-Analysis-Siam.pdf.pdf)

---

## 🚀 Future Improvements

This project will continue evolving with practical cybersecurity topics, including:

- Packet Capture & Analysis (Wireshark)
- Windows Event Logs
- Security Monitoring (SOC)
- Microsoft Sentinel
- Microsoft Azure Networking
- Identity & Access Management (IAM)
- Cloud Security Concepts

---

## 🎓 Learning Outcomes

Through this project, I strengthened my ability to:

- Explain internet communication from a cybersecurity perspective
- Identify common attack surfaces
- Understand defensive security controls
- Apply foundational security principles
- Think systematically about how modern systems communicate and where trust can fail.

## 📚 References

- Microsoft Learn
- TryHackMe
- OWASP Foundation
- NIST Cybersecurity Framework
- Cloudflare Learning Center
---

## 👨‍💻 About the Author

**MD Siam Babon**

Aspiring Cybersecurity Analyst with a strong interest in **Security Operations (SOC)**, **Microsoft Azure**, and **Cloud Security**.

Currently developing practical cybersecurity skills through hands-on labs, technical documentation, and security-focused projects while building a professional cybersecurity portfolio.

### 🌱 Learning Platforms

- TryHackMe
- Microsoft Learn
- GitHub

📧 **Email:** siambabon.it@gmail.com

🔗 **LinkedIn:** https://linkedin.com/in/siambabon

---

> **Disclaimer:** This project is intended for educational purposes and demonstrates foundational cybersecurity concepts. It does not include offensive exploitation techniques or instructions for unauthorized access.
