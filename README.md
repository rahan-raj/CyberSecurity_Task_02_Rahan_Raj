# CyberSecurity_Task_02_Rahan_Raj
This task covers the  Foundational concepts of Cybersecurity

> Submitted by: Rahan Raj K R    
> Date: June 2026  

---

# Part A: Understanding the CIA Triad

The **CIA Triad** is the foundation of all cybersecurity practices. Every security decision in an organization is guided by these three principles.

---

##  1. Confidentiality

### Definition
Confidentiality means ensuring that information is only accessible to those who are **authorized** to see it. Unauthorized individuals should not be able to view, copy, or access sensitive data.

### Why It Is Important
Without confidentiality, sensitive data — such as passwords, medical records, financial information, and personal details — can be exposed to attackers. This leads to identity theft, financial loss, legal penalties, and damage to an organization's reputation.

### Real-World Example
In **2013, Edward Snowden** leaked classified NSA (National Security Agency) documents. This was a major confidentiality breach — sensitive government information was accessed and shared with people who were not authorized to see it.

Another example: If a hospital's patient database is accessed by an unauthorized person, it violates confidentiality because private health records are exposed.

### How Confidentiality is Maintained
- Encryption (scrambling data so only authorized users can read it)
- Access controls (passwords, role-based access)
- Multi-Factor Authentication (MFA)
- Data classification policies

---

##  2. Integrity

### Definition
Integrity means ensuring that information is **accurate, complete, and has not been tampered with** — either accidentally or maliciously. Data should only be modified by authorized users through authorized processes.

### Why It Is Important
If data integrity is compromised, the information cannot be trusted. For example, if a hospital's medication records are altered by an attacker, a patient could receive the wrong dose of medicine — which could be life-threatening. In finance, altered records could lead to fraud.

### Real-World Example
In **2016, hackers attacked the Bangladesh Bank** and manipulated the SWIFT banking system's transaction records. They altered transfer instructions to steal $81 million. This was a direct integrity attack — the data was changed without authorization.

### How Integrity is Maintained
- Hashing (creating a digital fingerprint of data to detect changes)
- Digital signatures
- Version control systems
- Audit logs and monitoring
- Input validation

---

##  3. Availability

### Definition
Availability means ensuring that information, systems, and resources are **accessible and functional** when authorized users need them. Systems should be up and running — not blocked by attacks or failures.

### Why It Is Important
If a system is unavailable, the organization cannot function. A bank whose online services are down loses customers and money. A hospital whose systems crash during an emergency could put lives at risk. Availability ensures business continuity.

### Real-World Example
In **2016, the Dyn DNS DDoS Attack** took down major websites including Twitter, Netflix, Reddit, and Spotify for several hours. Attackers flooded the Dyn servers with traffic until they crashed — making those websites unavailable to millions of users worldwide.

### How Availability is Maintained
- Redundant systems and backups
- DDoS (Distributed Denial of Service) protection
- Load balancing
- Disaster recovery plans
- Regular maintenance and uptime monitoring

---

##  Comparison Table: CIA Triad

| Feature | Confidentiality | Integrity | Availability |
|---|---|---|---|
| **Goal** | Prevent unauthorized access to data | Ensure data is accurate and unaltered | Ensure systems are accessible when needed |
| **Protects Against** | Eavesdropping, data theft, leaks | Data tampering, corruption, unauthorized modification | Downtime, DoS attacks, system failures |
| **Key Question** | "Who can see this data?" | "Is this data trustworthy?" | "Can users access this data right now?" |
| **Common Threats** | Hacking, insider leaks, phishing | Man-in-the-middle attacks, malware, ransomware | DDoS attacks, hardware failure, ransomware |
| **Key Controls** | Encryption, access control, MFA | Hashing, digital signatures, audit logs | Backups, redundancy, DDoS protection |
| **Real-World Example** | NSA Snowden Leak (2013) | Bangladesh Bank Heist (2016) | Dyn DDoS Attack (2016) |
| **Impact if Broken** | Privacy violations, identity theft | Data corruption, fraud, misinformation | Business disruption, financial loss |

---
# Part B: Real-World Case Study — WannaCry Ransomware Attack (2017)

## What Happened?

In **May 2017**, a massive cyberattack known as **WannaCry** spread across the globe within hours. It was a type of **ransomware** — malicious software that encrypts a victim's files and demands a ransom payment to restore access.

WannaCry targeted computers running **Microsoft Windows**. It exploited a critical vulnerability called **EternalBlue** — a flaw in the Windows SMB (Server Message Block) protocol. This exploit had actually been discovered and used by the **US National Security Agency (NSA)** but was later stolen and leaked online by a hacker group called **The Shadow Brokers**.

The attack spread like a worm — it didn't need users to click a link or open an email. Once inside a network, it automatically scanned for other vulnerable computers and infected them too. Within just a few days, WannaCry had infected over **200,000 computers in 150 countries**.

---

| Category | Details |
|---|---|
| **Attack Name** | WannaCry Ransomware |
| **Date** | May 12, 2017 |
| **Type of Attack** | Ransomware + Worm |
| **Vulnerability Exploited** | EternalBlue (CVE-2017-0144) in Windows SMB |
| **Systems Affected** | Windows XP, 7, Server 2003/2008 |
| **Countries Affected** | 150+ countries |
| **Machines Infected** | 200,000+ |
| **Financial Damage** | $4–8 billion USD |
| **CIA Triad Impact** | Availability (High), Integrity (High), Confidentiality (Medium) |
| **Could Have Been Prevented By** | Patching MS17-010, backups, network segmentation |

---

# Part C: Risk Assessment Activity — College Security Analyst

> **Scenario:** You are a Security Analyst for a college. Your job is to identify assets that need protection, the threats they face, their potential impact, and the overall risk level.

##  Risk Assessment Table

| # | Asset | Threat | Impact | Risk Level |
|---|-------|--------|--------|------------|
| 1 | **Student Records** | Data Breach / Unauthorized Access | Personal data of thousands of students exposed; identity theft; legal penalties under data protection laws | 🔴 High |
| 2 | **Examination Data** | Insider Leak / Hacking | Exam papers leaked before exams; academic integrity destroyed; reputation damage to the college | 🔴 High |
| 3 | **College Website** | DDoS Attack / Defacement | Website goes offline during admissions; public misinformation if content is changed; reputation damage | 🟡 Medium |
| 4 | **Faculty & Staff Information** | Phishing / Data Theft | Personal and financial details of staff exposed; payroll fraud; unauthorized access to internal systems | 🔴 High |
| 5 | **Network Infrastructure** | Malware / Ransomware | Entire college network goes down; all digital services disrupted; recovery is costly and time-consuming | 🔴 Critical |
| 6 | **Financial Records** | Fraud / Unauthorized Access | Theft of college funds; manipulation of fee payment records; legal and regulatory consequences | 🔴 Critical |
| 7 | **Learning Management System (LMS)** | Account Hijacking / Malware | Students cannot access online classes; grades tampered with; academic disruption | 🟡 Medium |
| 8 | **Email System** | Phishing / Spoofing | Staff and students tricked into revealing credentials; malware spread through malicious attachments | 🟡 Medium |
| 9 | **CCTV / Physical Security Systems** | Unauthorized Access / Tampering | Security footage deleted or manipulated; physical safety of campus compromised | 🟡 Medium |
| 10 | **Library & Research Databases** | Unauthorized Access / IP Theft | Paid academic content stolen; student research data exposed; access to licensed material lost | 🟠 Medium-High |

---

# Part D: Threat Identification & Analysis

This section explains five major cybersecurity threats, their potential impact, and how to prevent them.

## 1.  Insider Threat

An **insider threat** occurs when someone **within the organization** — such as a current or former employee, contractor, or partner — misuses their authorized access to cause harm. This can be intentional (malicious insider) or accidental (negligent insider).

## 2.  Malware

**Malware** (short for Malicious Software) is any software **intentionally designed to cause damage** to a computer system, network, or user. It is one of the most common and dangerous cyber threats.

## 3.  Phishing

**Phishing** is a type of **social engineering attack** where an attacker disguises themselves as a trustworthy entity (a bank, a manager, a popular website) to trick users into revealing sensitive information such as passwords, credit card numbers, or login credentials.

## 4.  Weak Passwords

**Weak passwords** are passwords that are short, simple, common, or easy to guess — making it straightforward for attackers to gain unauthorized access to accounts and systems.

## 5.  Unpatched Systems

**Unpatched systems** are computers, software, or devices that have not had their **security updates** (patches) applied. Software developers regularly release patches to fix known security vulnerabilities. When organizations fail to apply these updates, they leave known security holes open for attackers to exploit.

> Detailed overview about the threats can be viewed in `/Threat Analysis` folder which contains **Description,Possible Impact,Prevention Methods**.

 ---

 # Part E: Security Recommendations

Based on the risk assessment of the college environment, here are **10 essential security recommendations** with explanations for why each one matters.

1: Enable Multi-Factor Authentication (MFA)
2: Regular System & Software Updates (Patch Management)
3: Strong Password Policy
4: Employee & Student Security Awareness Training
5: Regular Data Backups
6: Network Segmentation
7: Antivirus & Anti-Malware Software
8: Access Control & Least Privilege Principle
9: Incident Response Plan
10: Regular Security Audits & Vulnerability Assessments

> Detailed informations about the 10 Recommendations can be found in `/Security Recommendations` folder.

---

# Part F: Mini Security Consultant Report

## Executive Summary

Following a thorough review of the college's digital assets, infrastructure, and current security practices, this report identifies the **top five cybersecurity risks** currently facing the institution and provides **five targeted recommendations** to address them. Implementing these measures will significantly strengthen the college's security posture, protect student and staff data, ensure business continuity, and support compliance with data protection regulations.

---

## Top 5 Risks
1: Unpatched & Outdated Systems
2: Phishing & Social Engineering Attacks
3: Ransomware & Malware Infection
4: Unauthorized Access Due to Weak Authentication
5: Insider Threats & Excessive Access Privileges

---

## Top 5 Recommendations
1: Implement a Formal Patch Management Programme
2: Deploy Multi-Factor Authentication (MFA) Across All Systems
3: Launch an Ongoing Security Awareness Training Programme
4: Implement the 3-2-1 Backup Strategy
5: Enforce Least Privilege Access Control & Strengthen Offboarding

> For more details refer the folder `/Consultant Report` 

---

