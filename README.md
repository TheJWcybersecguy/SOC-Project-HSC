# HSC SOC Internship Projects

This repository contains investigations and incident response case studies completed during the HSC SOC Internship Program.

The projects demonstrate practical skills in:

- Threat Hunting
- Log Analysis
- Memory Forensics
- Malware Analysis
- Incident Response
- Cloud Security
- MITRE ATT&CK Mapping
- Network Analysis

## Projects

### Task 1 – PowerShell Malware Investigation
**Objective:** Investigate suspicious Sysmon logs and identify malicious PowerShell activity.

**Key Findings**
- Suspicious connection to 192[.]168[.]10[.]45
- PowerShell used as a LOLBin
- Persistence via Scheduled Tasks
- Base64-encoded payload downloaded and executed remotely

**Skills Demonstrated**
- Sysmon Analysis
- Threat Hunting
- PowerShell Analysis
- Persistence Detection

### Task 2 – Memory Forensics and Process Hollowing
**Objective:** Analyze a memory image and identify evidence of process injection.

**Key Findings**
- Compromised Process: svchost.exe
- Suspicious Parent: notepad.exe
- RWX memory region detected
- PE headers (MZ) found in memory
- C2 communication identified

**Skills Demonstrated**
- Memory Forensics
- Malware Analysis
- Process Injection Detection
- Network Analysis

### Task 3 – Cloud Security Incident Response
**Objective:** Investigate a cloud compromise involving stolen AWS credentials.

**Key Findings**
- Stolen AWS Access Key identified
- Administrative privileges granted via PutUserPolicy
- Sensitive S3 file exfiltrated
- Backdoor user created
- Original access key disabled

**Skills Demonstrated**
- AWS Security
- Cloud Forensics
- Incident Response
- Credential Theft Investigation

### Task 4 – Cryptocurrency Miner Incident Response
**Objective:** Investigate and remediate a compromised Windows workstation.

**Key Findings**
- Malicious process identified
- Macro-enabled document used as initial vector
- Malware downloaded via certutil
- Registry persistence discovered
- C2 infrastructure identified

**Skills Demonstrated**
- Incident Response
- Malware Analysis
- Registry Analysis
- Windows Forensics

## MITRE ATT&CK Techniques Covered

- T1055.012 – Process Hollowing
- T1078 – Valid Accounts
- T1098 – Account Manipulation
- T1136 – Create Account
- T1059.001 – PowerShell
- T1547.001 – Registry Run Keys
- T1071 – Application Layer Protocol

## Author

Odebiyi Musa
