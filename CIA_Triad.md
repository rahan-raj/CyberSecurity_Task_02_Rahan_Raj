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

> 💡 **Key Insight:** In real attacks, often more than one part of the CIA Triad is affected. For example, ransomware attacks affect both **Integrity** (data is encrypted/corrupted) and **Availability** (systems become inaccessible).
