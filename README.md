Name: JAGAN.M
Company:  Codtech IT Solutions Private Limited
ID: CTTS036
Domain: CYBER SECURITY AND ETHICAL HACKING
Duration: 25 May 2026 - 22 June 2026
Mentor: Neela Santhosh Kumar 



# File Integrity Monitor (FIM)

## Project: Cyber Security and Ethical Hacking

### 1. Introduction

File Integrity Monitoring (FIM) is a cybersecurity technique used to detect unauthorized changes to files and directories. It helps security professionals identify suspicious activities such as file modifications, deletions, or the creation of new files that may indicate a cyberattack or system compromise.

This project is developed using Python and utilizes the SHA-256 hashing algorithm to monitor the integrity of files. By comparing current file hashes with a previously generated baseline, the system can detect and alert users about any changes in monitored files.

---

### 2. Problem Statement

Critical files within a system may be modified, deleted, or replaced by attackers without the knowledge of system administrators. Such unauthorized changes can lead to data breaches, malware infections, or system compromise. Therefore, an automated monitoring system is required to detect and report file integrity violations in real time.

---

### 3. Objective

The main objectives of this project are:

* To monitor important files and directories.
* To detect unauthorized file modifications.
* To identify newly created files.
* To detect file deletions.
* To provide real-time security alerts.
* To demonstrate the use of cryptographic hashing in cybersecurity.

---

### 4. Project Description

The File Integrity Monitor creates a baseline database containing SHA-256 hashes of files within a target directory. During monitoring, the program continuously scans the directory and compares current file hashes with the baseline values.

The system can detect:

* File Modifications
* File Deletions
* New File Creations
* Unauthorized Changes to Critical Files

Whenever a change is detected, the program generates an alert with a timestamp, allowing administrators to investigate the event.

---

### 5. Technologies Used

* **Programming Language:** Python
* **Libraries:** os, hashlib, json, time, datetime
* **Hashing Algorithm:** SHA-256
* **Platform:** Windows/Linux/Mac
* **IDE:** VS Code, PyCharm, or Python IDLE

---

### 6. Working of the System

1. The user selects a directory to monitor.
2. The program generates a baseline containing SHA-256 hashes of all files.
3. The baseline data is stored in a JSON file.
4. The monitoring mode continuously scans the directory.
5. Current file hashes are compared with baseline hashes.
6. If a file is modified, deleted, or newly created, an alert is generated.
7. The monitoring process continues until stopped by the user.

---

### 7. Cybersecurity Importance

File Integrity Monitoring is widely used in cybersecurity to detect unauthorized changes and maintain system security. This project supports:

* Intrusion Detection
* Malware Detection
* Security Monitoring
* Incident Response
* Compliance Monitoring
* System Integrity Verification

FIM solutions are commonly used by organizations to protect critical systems and sensitive data from unauthorized modifications.

---

### 8. Advantages

* Detects unauthorized file changes.
* Provides real-time monitoring.
* Uses secure SHA-256 hashing.
* Generates clear security alerts.
* Easy to deploy and customize.
* Improves overall system security.

---

### 9. Expected Output

**Baseline Generation:**

```text
==================================================
        Python File Integrity Monitor (FIM)
==================================================

[+] Generating baseline schema for: ./critical_files
[+] Baseline successfully generated with 10 tracked files.
[+] Baseline saved to: fim_baseline.json
```

**Monitoring Mode:**

```text
[+] Monitoring loop active for './critical_files'...

[2026-06-18 15:30:10] 🚨 ALERT: File Modified! -> ./critical_files/report.txt

[2026-06-18 15:31:25] ⚠️ ALERT: New File Created -> ./critical_files/newfile.txt

[2026-06-18 15:32:40] ❌ ALERT: File Deleted! -> ./critical_files/config.txt
```

---

### 10. Conclusion

The File Integrity Monitor (FIM) is an effective cybersecurity project that helps detect unauthorized changes to files and directories. By using SHA-256 hashing and continuous monitoring, the system can quickly identify file modifications, deletions, and new file creations. This project provides practical experience in security monitoring, intrusion detection, and cryptographic hashing while demonstrating an important defensive cybersecurity technique used in real-world environments.
