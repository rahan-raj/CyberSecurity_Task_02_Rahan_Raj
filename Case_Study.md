# Part B: Real-World Case Study — WannaCry Ransomware Attack (2017)

---

##  What Happened?

In **May 2017**, a massive cyberattack known as **WannaCry** spread across the globe within hours. It was a type of **ransomware** — malicious software that encrypts a victim's files and demands a ransom payment to restore access.

WannaCry targeted computers running **Microsoft Windows**. It exploited a critical vulnerability called **EternalBlue** — a flaw in the Windows SMB (Server Message Block) protocol. This exploit had actually been discovered and used by the **US National Security Agency (NSA)** but was later stolen and leaked online by a hacker group called **The Shadow Brokers**.

The attack spread like a worm — it didn't need users to click a link or open an email. Once inside a network, it automatically scanned for other vulnerable computers and infected them too. Within just a few days, WannaCry had infected over **200,000 computers in 150 countries**.

---

##  Which Part of the CIA Triad Was Affected?

WannaCry primarily attacked **two parts** of the CIA Triad:

### 1. Availability — SEVERELY IMPACTED ❌
This was the most visible damage. When WannaCry infected a system, it **locked users out completely**. Hospitals couldn't access patient records. Factories shut down production lines. Banks couldn't process transactions. Users saw a ransom message instead of their files — the systems were simply unavailable.

### 2. Integrity — IMPACTED ❌
WannaCry **encrypted all data** on infected machines, which means the data was altered without authorization. Files were no longer in their original, usable state. The integrity of the data was destroyed — users couldn't trust or use their own files.

### 3. Confidentiality — PARTIALLY IMPACTED ⚠️
While WannaCry's main goal was ransom (not data theft), there was a risk that attackers could also **steal sensitive information** before encrypting it. Some researchers believe data may have been exfiltrated in certain cases.

---

##  What Was the Impact?

The impact of WannaCry was massive and affected people and organizations worldwide:

- **NHS (UK National Health Service):** Over 80 hospitals and medical organizations were hit. Surgeries had to be cancelled, ambulances were diverted, and doctors could not access patient records. This put lives at risk.

- **Renault-Nissan (France/UK):** Car production facilities had to be shut down because factory systems were infected.

- **FedEx (USA):** The global delivery company reported significant disruption to its operations.

- **Telefónica (Spain):** One of the world's largest telecoms companies was badly affected.

- **Financial Damage:** The total global financial damage was estimated at **$4–8 billion USD**.

- **Ransom Demanded:** Attackers demanded $300–$600 in **Bitcoin** per infected machine.

- **Lives at Risk:** Because hospitals were targeted, patients in critical care were put at serious risk when records and monitoring systems went offline.

---

##  How Could It Have Been Prevented?

Several measures could have prevented or greatly limited the damage from WannaCry:

### 1. Patch Management (Most Critical)
Microsoft had actually released a security patch called **MS17-010** two months before the attack in March 2017. Organizations that had applied this update were NOT affected. The NHS and many others were running **outdated, unpatched Windows systems** — some even Windows XP, which Microsoft no longer supported. Regular patching would have blocked the attack entirely.

### 2. Network Segmentation
If hospital or corporate networks had been properly **segmented** (divided into isolated sections), the worm would not have been able to spread across the entire organization. Containment would have been much faster.

### 3. Regular Backups
Organizations with up-to-date, **offline backups** could have simply restored their data without paying the ransom. Many victims had no reliable backup systems in place.

### 4. Disabling Unnecessary Services
The SMB protocol used by EternalBlue could have been **disabled or restricted** on systems that didn't need it. This would have removed the attack surface entirely.

### 5. Employee Awareness Training
While WannaCry spread automatically, many ransomware attacks begin with phishing emails. Training staff to recognize suspicious emails reduces the initial risk of malware entering the network.

### 6. Endpoint Security
Up-to-date **antivirus and anti-malware software** with real-time threat detection would have flagged and blocked WannaCry on many systems.

---

##  Summary

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

> 💡 **Lesson Learned:** WannaCry is a perfect example of why **patch management** and **regular backups** are not optional — they are critical. A patch that had been available for two months could have prevented billions in damages and protected patient lives.
