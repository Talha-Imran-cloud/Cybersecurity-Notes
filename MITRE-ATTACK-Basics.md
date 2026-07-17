# MITRE ATT&CK Basics

## What is MITRE ATT&CK?

MITRE ATT&CK is a knowledge base that documents real-world attacker behavior.

It helps security teams understand:

- How attackers gain access
- What actions they perform
- How to detect attacks
- How to respond to incidents

## Why is MITRE ATT&CK Important?

SOC analysts use MITRE ATT&CK to:

- Investigate alerts
- Understand attacker behavior
- Map incidents to techniques
- Improve detections

## ATT&CK Lifecycle

### Initial Access

The attacker gains entry into the environment.

Examples:

- Phishing
- Exploiting Public Applications
- Valid Accounts

---

### Execution

The attacker executes code.

Examples:

- PowerShell
- Command Prompt
- Scripts

---

### Persistence

The attacker maintains access.

Examples:

- New User Creation
- Scheduled Tasks
- Startup Entries

---

### Privilege Escalation

The attacker attempts to gain higher privileges.

Examples:

- Administrator Access
- Domain Admin Access

---

### Defense Evasion

The attacker attempts to avoid detection.

Examples:

- Disabling Antivirus
- Log Deletion

---

### Credential Access

The attacker steals credentials.

Examples:

- Password Dumping
- Keylogging

---

### Discovery

The attacker gathers information.

Examples:

- whoami
- ipconfig
- net user

---

### Lateral Movement

The attacker moves to other systems.

Examples:

- RDP
- SMB
- PsExec

---

### Collection

The attacker collects sensitive data.

Examples:

- Documents
- Databases
- Credentials

---

### Exfiltration

The attacker sends stolen data outside the organization.

Examples:

- Cloud Storage
- HTTP Uploads
- FTP

## SOC Analyst Example

Phishing Email
↓
PowerShell Execution
↓
New User Created
↓
Admin Rights Assigned
↓
Data Stolen

MITRE Mapping:

- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Collection
- Exfiltration

## Common Techniques

- T1566 - Phishing
- T1059.001 - PowerShell
- T1136 - Create Account
- T1110 - Brute Force
- T1190 - Exploit Public-Facing Application
