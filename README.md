# cyber-security-task-3
# 🔍 Vulnerability Scan on Local Machine Using Nessus Essentials

## 📌 Task Overview

As part of the Cybersecurity Internship Task 3, I performed a **basic vulnerability scan** on my personal computer using **Nessus Essentials**. The objective was to identify common vulnerabilities and understand risk levels, CVSS scores, and remediation steps.

---

## 🛠 Tools Used

- **Nessus Essentials** by Tenable (Free version)
- **Web Interface** accessed at `https://localhost:8834`
- Operating System: Windows 10/11

---

## 📋 Steps Followed

1. **Installed Nessus Essentials**  
   - Registered on Tenable website to get the free activation code.  
   - Installed Nessus and accessed the dashboard via browser at `https://localhost:8834`.  

2. **Configured Scan**  
   - Created a new "Basic Network Scan".
   - Set the target as `localhost (127.0.0.1)`.

3. **Ran the Scan**  
   - Waited for plugin download and scan completion (around 30–45 minutes).

4. **Analyzed Results**  
   - Reviewed the vulnerabilities found.
   - Focused on **High** and **Critical** severity issues.
   - Noted CVSS scores and recommended remediation steps.

5. **Documented Findings**  
   - Took screenshots of scan summary and selected vulnerabilities.
   - Compiled results and uploaded them to this repository.

---

## 📸 Screenshots

Screenshots of the scan results and key vulnerabilities can be found in the `/screenshots` folder.

---

## 🔒 Key Vulnerabilities Found

| Vulnerability Title                | Severity | CVSS Score | Suggested Fix                        |
|------------------------------------|----------|------------|--------------------------------------|
| Example: Outdated OpenSSH version | High     | 8.1        | Update to latest OpenSSH release    |
| Example: SMB Signing Not Required | Medium   | 6.5        | Enforce SMB signing in group policy |

> *(Actual results may vary — replace with real findings.)*

---

## 🧠 Key Concepts Learned

- Vulnerability Scanning vs. Penetration Testing
- CVSS (Common Vulnerability Scoring System)
- False positives in scans
- Prioritizing vulnerabilities based on severity and exploitability
- Importance of patch management and system hardening

---

## 📁 Files Included

- `README.md` – this file
- `/screenshots/` – images of scan and findings
- `scan_report.pdf` *(optional)* – exported scan report from Nessus

---

## 🔗 Submission

Task submitted via [Google Form](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## ✅ Status

✔️ Task Completed  
🕵️ Report Submitted  
📚 Ready for Review
