# Part D: Threat Identification & Analysis

This section explains five major cybersecurity threats, their potential impact, and how to prevent them.

---

## 1.  Insider Threat

### Description
An **insider threat** occurs when someone **within the organization** — such as a current or former employee, contractor, or partner — misuses their authorized access to cause harm. This can be intentional (malicious insider) or accidental (negligent insider).

There are three types:
- **Malicious Insider:** Deliberately steals, leaks, or destroys data for personal gain, revenge, or on behalf of a competitor/attacker.
- **Negligent Insider:** Accidentally causes a breach through careless behavior (e.g., losing a USB drive, clicking a phishing link, misconfiguring a system).
- **Compromised Insider:** A legitimate user whose credentials have been stolen by an attacker who then acts on their behalf.

### Possible Impact
- Theft of intellectual property, trade secrets, or sensitive data
- Sabotage of systems or databases
- Financial fraud (e.g., redirecting payments)
- Reputational damage that is very hard to recover from
- Legal consequences for the organization

### Prevention Methods
- **Least Privilege Principle:** Give employees only the access they need to do their job — nothing more.
- **User Activity Monitoring (UAM):** Monitor and log what users are accessing, especially sensitive systems.
- **Background Checks:** Perform thorough background checks during hiring.
- **Access Reviews:** Regularly review and revoke access for employees who change roles or leave.
- **Offboarding Procedures:** Immediately disable all accounts when an employee leaves the company.
- **Security Culture:** Train employees to report suspicious behavior from colleagues.

---

## 2.  Malware

### Description
**Malware** (short for Malicious Software) is any software **intentionally designed to cause damage** to a computer system, network, or user. It is one of the most common and dangerous cyber threats.

Common types of malware include:
- **Virus:** Attaches itself to legitimate files and spreads when those files are shared.
- **Worm:** Self-replicates and spreads across networks without any user action.
- **Ransomware:** Encrypts files and demands payment for the decryption key (e.g., WannaCry).
- **Trojan Horse:** Disguises itself as a legitimate program but carries malicious code inside.
- **Spyware:** Secretly monitors user activity and sends data back to the attacker.
- **Keylogger:** Records every keystroke a user makes to steal passwords and credentials.
- **Rootkit:** Gives an attacker deep, hidden access to a system while hiding its presence.

### Possible Impact
- Complete loss of data (ransomware)
- Financial theft (banking trojans, keyloggers)
- Unauthorized access to sensitive systems
- System slowdown, crashes, or complete failure
- Espionage — stealing trade secrets or government intelligence

### Prevention Methods
- **Antivirus & Anti-Malware Software:** Install and keep updated on all devices.
- **Regular System Updates:** Malware often exploits vulnerabilities in outdated software.
- **Email Filtering:** Block malicious attachments and links in emails before they reach users.
- **Application Whitelisting:** Only allow approved software to run on systems.
- **Regular Backups:** Maintain offline backups so ransomware attacks don't result in permanent data loss.
- **User Training:** Teach staff not to download unverified software or click suspicious links.

---

## 3. Phishing

### Description
**Phishing** is a type of **social engineering attack** where an attacker disguises themselves as a trustworthy entity (a bank, a manager, a popular website) to trick users into revealing sensitive information such as passwords, credit card numbers, or login credentials.

Common phishing methods:
- **Email Phishing:** Fake emails claiming to be from banks, tech companies (Google, Microsoft), or HR departments asking users to "verify" their account.
- **Spear Phishing:** Targeted phishing aimed at a specific individual, often with personalized details to seem more convincing.
- **Smishing:** Phishing via SMS text messages.
- **Vishing:** Phishing via phone calls (voice phishing).
- **Whaling:** Targeting high-profile individuals like CEOs or CFOs.

### Possible Impact
- Credential theft (passwords, login details)
- Financial fraud — bank account access, unauthorized transactions
- Ransomware or malware installation (malicious links/attachments)
- Identity theft
- Corporate espionage (compromising executive accounts)

### Prevention Methods
- **Security Awareness Training:** Regularly train employees to spot phishing emails (poor grammar, urgent language, suspicious sender addresses).
- **Multi-Factor Authentication (MFA):** Even if a password is stolen, MFA prevents account access.
- **Email Filtering Tools:** Tools like Microsoft Defender or spam filters can detect and block phishing emails.
- **Check Sender Details:** Always verify the actual email address — not just the display name.
- **Never Click Suspicious Links:** Go directly to websites rather than clicking email links.
- **Report Phishing Attempts:** Encourage a culture where staff immediately report suspicious emails to IT.

---

## 4.  Weak Passwords

### Description
**Weak passwords** are passwords that are short, simple, common, or easy to guess — making it straightforward for attackers to gain unauthorized access to accounts and systems.

Weak password examples:
- Using simple words: `password`, `hello`, `qwerty`
- Using personal information: date of birth, name, phone number
- Short passwords under 8 characters
- Reusing the same password across multiple accounts
- Never changing default passwords on devices and systems

Attackers use various techniques to crack weak passwords:
- **Brute Force:** Trying every possible combination until one works.
- **Dictionary Attack:** Trying common words and phrases from a pre-built list.
- **Credential Stuffing:** Using leaked username/password pairs from previous data breaches.

### Possible Impact
- Unauthorized access to accounts, systems, and data
- Account takeovers leading to data theft or financial fraud
- A single compromised account can give attackers access to an entire network
- Regulatory fines if sensitive data is exposed due to poor password practices

### Prevention Methods
- **Strong Password Policy:** Require passwords of at least 12 characters with a mix of uppercase, lowercase, numbers, and symbols.
- **Password Managers:** Tools like Bitwarden or LastPass help users create and store complex, unique passwords.
- **Multi-Factor Authentication (MFA):** Adds a second layer of security even if a password is compromised.
- **Prohibit Password Reuse:** Force users to create new, unique passwords and not reuse old ones.
- **Account Lockout Policies:** Lock accounts after a certain number of failed login attempts to block brute force attacks.
- **Change Default Passwords:** Always change factory-default passwords on all devices, routers, and systems immediately.

---

## 5.  Unpatched Systems

### Description
**Unpatched systems** are computers, software, or devices that have not had their **security updates** (patches) applied. Software developers regularly release patches to fix known security vulnerabilities. When organizations fail to apply these updates, they leave known security holes open for attackers to exploit.

This is one of the most common causes of successful cyberattacks. The WannaCry ransomware attack (2017) is a perfect example — it exploited a Windows vulnerability for which a patch had been available for **two months** before the attack.

### Possible Impact
- Exploitation of known vulnerabilities to gain unauthorized access
- Malware and ransomware infections through unpatched flaws
- Complete system compromise — attackers can gain full control
- Data breaches and theft of sensitive information
- Non-compliance with data protection regulations (e.g., GDPR), leading to fines

### Prevention Methods
- **Patch Management Policy:** Establish a formal process for regularly reviewing and applying security patches.
- **Automated Updates:** Enable automatic updates for operating systems and critical software where possible.
- **Vulnerability Scanning:** Use tools (e.g., Nessus, Qualys) to regularly scan for known vulnerabilities.
- **Prioritize Critical Patches:** Apply critical security patches immediately — within 24–48 hours of release.
- **Asset Inventory:** Maintain a complete list of all software and systems in use so no system is forgotten.
- **End-of-Life Software:** Replace software that is no longer supported by the manufacturer, as it will no longer receive security updates.

---

##  Threat Summary Table

| Threat | Main Risk | Top Prevention |
|---|---|---|
| Insider Threat | Data theft/sabotage by trusted users | Least privilege + access monitoring |
| Malware | System damage, data encryption/theft | Antivirus + regular updates |
| Phishing | Credential theft through deception | Staff training + MFA |
| Weak Passwords | Unauthorized account access | Strong password policy + MFA |
| Unpatched Systems | Exploitation of known vulnerabilities | Regular patching + vulnerability scans |
