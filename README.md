# DF-Project---Digital-Crime-Scene-Investigation

# M57 Jean Digital Forensics Project  
**A Case Study on Phishing-Induced Data Breach Investigation**  

---

##  Project Overview  
This repository documents a digital forensics investigation conducted for **M57.biz**, a startup implicated in a corporate espionage incident. The project focuses on analyzing a data breach involving CFO Jean Jones' laptop, where a confidential employee spreadsheet was leaked to a competitor. Key objectives include validating email communications, identifying phishing attempts, and assessing GDPR compliance.  

---

##  Key Phases of the Investigation  
### 1. **Identification**  
- Recognized a data breach involving leaked employee PII (Social Security Numbers, salaries).  
- Defined objectives: Validate Jean’s claims, trace data exfiltration, and identify phishing activities.  

### 2. **Collection/Preservation**  
- Secured Jean’s laptop and created a forensic image (`nps-2008-jean.E01`) using a write blocker.  
- Maintained chain of custody.  
- Verified data integrity with MD5 hashing.  

### 3. **Analysis**  
- Extracted and analyzed emails from `Outlook.pst` using **CoolUtils PST Reader**.  
- Identified spoofed emails (e.g., `alex@m57.biz` impersonating CEO Alison Smith).  
- Reconstructed the attack timeline.  

### 4. **Documentation**  
- Compiled forensic logs, GDPR compliance assessments, and legal chain-of-custody records.  

### 5. **Presentation**  
- Concluded Jean was a victim of spear-phishing, not malicious intent.  
- Provided recommendations for improving organizational cybersecurity.  

---

## Tools & Technologies  
| **Tool**               | **Purpose**                                  |  
|------------------------|----------------------------------------------|  
| FTK Imager v4.7.3      | Disk imaging and integrity verification.     |  
| CoolUtils PST Reader   | Extracting and analyzing Outlook emails.     |  
| MD5 Hash Generator     | Ensuring data integrity during preservation. |  

---

##  Repository Structure  
```plaintext
M57-Jean-Forensics/  
├── Evidence/  
│   ├── nps-2008-jean.E01          # Forensic disk image  
│   └── nps-2008-jean.E02          # Disk image continuation  
├── Reports/  
│   ├── DF-project-Documentation.pdf        # Full investigation report  
│   
