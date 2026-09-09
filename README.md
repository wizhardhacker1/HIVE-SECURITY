<img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/d1333dc6-9464-4897-9c1b-46d23cd50450" /> Buy me a Coffee- buymeacoffee.com/wizhardhacker1


<img width="1890" height="886" alt="image" src="https://github.com/user-attachments/assets/c6db6677-8c60-41ef-b592-a8e80e06ecc8" />
<br>

** Added Cert for Hive Security  
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/4e29fcec-64ea-4802-92fc-e47c3a7e139d" />


Local-First Cybersecurity Operations, Threat Intelligence, Vulnerability Management, Red/Blue/Purple Team Operations, Compliance & Security Training


**HIVE SECURITY** is a Windows-focused, local-first cybersecurity operations platform that combines threat intelligence, vulnerability assessment, incident response, penetration-test reporting, exposure management, compliance, detection engineering, Red/Blue/Purple Team operations, security education, reporting, and local AI in one unified workspace.

> **SIGNAL → INVESTIGATE → REMEDIATE → VALIDATE → ASSURE**

---

## 🚀 HIVE SECURITY 0.7.5

HIVE SECURITY 0.7.5 expands the platform with a visual **Interactive Cyber Kill Chain** containing operational Red Team, Blue Team, and Purple Team command references across the full attack lifecycle.

### Major capabilities

- 🖥️ Unified Security Operations
- 🌎 Global Threat Activity
- 🧠 IOC Intelligence Center
- 📰 Cyber News
- 🔗 OSINT & Intelligence Launchpad
- ⛓️ Interactive Cyber Kill Chain
- 🔴 Red Team Workspace
- 🔵 Blue Team Workspace
- 🟣 Purple Team Workspace
- 🔎 Built-In Pentest Scanner
- 🔐 Credentialed Scanning
- ⏱️ Scheduled Scanning
- 🖥️ Asset Intelligence
- 🧬 CVE / CISA KEV Correlation
- 🎯 Exposure Management
- 🚨 SOC / Incident Response
- 🕵️ Investigations
- 🔒 Evidence Locker
- 📄 Pentest Report Management
- 🛠️ Remediation Queue
- 🛡️ STIG Compliance
- 📡 Detection Engineering
- 🎯 MITRE ATT&CK Coverage
- 👁️ Watchlists
- 🔔 Notifications
- 📋 Risk & GRC
- 📊 Executive Reporting
- 📚 Security Academy
- 👥 User / Certification Management
- 🤖 Local AI — Meta Llama 3.2 3B
- 🧰 Analyst Toolbox

---

# ⛓️ INTERACTIVE CYBER KILL CHAIN

HIVE SECURITY 0.7.5 introduces a visual and interactive Cyber Kill Chain workspace.

The seven stages are presented as a connected operational workflow:

```text
┌──────────────────┐
│  RECONNAISSANCE  │
└────────┬─────────┘
         ↓
┌──────────────────┐
│  WEAPONIZATION   │
└────────┬─────────┘
         ↓
┌──────────────────┐
│     DELIVERY     │
└────────┬─────────┘
         ↓
┌──────────────────┐
│   EXPLOITATION   │
└────────┬─────────┘
         ↓
┌──────────────────┐
│   INSTALLATION   │
└────────┬─────────┘
         ↓
┌──────────────────┐
│ COMMAND & CONTROL│
└────────┬─────────┘
         ↓
┌──────────────────┐
│    ACTIONS ON    │
│    OBJECTIVES    │
└──────────────────┘
```

Select a phase to examine the activity from three different perspectives:

```text
🔴 RED TEAM
   ↓
How would an authorized tester assess this stage?

🔵 BLUE TEAM
   ↓
How can defenders discover and investigate the activity?

🟣 PURPLE TEAM
   ↓
How can both teams safely validate the organization's visibility?
```

---

## ⚡ 138+ Kill Chain Commands & Actions

HIVE SECURITY contains more than **138 Red, Blue, and Purple Team command/action references** distributed across the seven Kill Chain stages.

Commands include:

- Team designation
- Kill Chain phase
- Command
- Description
- Operational purpose
- Usage guidance
- Copy Command control

This turns the Kill Chain from a static diagram into an operational security reference.

---

# 🔴 RECONNAISSANCE

Red Team reconnaissance focuses on authorized information gathering and exposure discovery.

Examples include:

```powershell
Resolve-DnsName example.com
```

```cmd
nslookup example.com
```

```bash
dig example.com
```

```bash
whois example.com
```

```bash
curl -I https://example.com
```

```bash
openssl s_client -connect example.com:443
```

Activities include:

- DNS enumeration
- WHOIS research
- Certificate transparency
- HTTP inspection
- TLS inspection
- Route discovery
- Service exposure
- Public infrastructure research

Blue Team commands focus on detecting reconnaissance through:

- DNS logs
- Firewall logs
- Proxy logs
- Connection telemetry
- Endpoint telemetry

Purple Team activities validate whether reconnaissance is visible to defenders.

---

# 🔴 WEAPONIZATION

Weaponization is represented through safe artifact-analysis and defensive-validation workflows rather than malware creation.

Activities include:

- File hashing
- File metadata
- Digital signatures
- String extraction
- Defender inspection
- Artifact validation
- File telemetry
- Detection testing

Example:

```powershell
Get-FileHash .\sample.bin -Algorithm SHA256
```

HIVE SECURITY intentionally does not provide malware-generation or weaponized-payload creation commands.

---

# 📦 DELIVERY

The Delivery stage focuses on identifying and validating mechanisms used to transfer suspicious content.

Activities include:

- HTTP inspection
- Redirect analysis
- TLS inspection
- File download telemetry
- PowerShell logging
- Process creation
- Defender events
- Email/web delivery visibility

Blue Team examples can include investigation of:

```text
Windows Event ID 4104
PowerShell Script Block Logging
```

and:

```text
Windows Event ID 4688
Process Creation
```

Purple Team workflows help validate whether delivery-related telemetry reaches the organization's monitoring systems.

---

# 💥 EXPLOITATION

This stage focuses on vulnerability and exposure validation without automatically exploiting targets.

Activities include:

- Service identification
- Version assessment
- HTTP method inspection
- Security headers
- TLS configuration
- SMB configuration
- Patch inventory
- Vulnerability correlation
- Detection validation

HIVE SECURITY does not automatically launch exploit payloads.

---

# 🧩 INSTALLATION

Installation focuses primarily on identifying persistence mechanisms and system changes.

Defensive checks can include:

```powershell
Get-Service
```

```powershell
Get-ScheduledTask
```

```powershell
Get-CimInstance Win32_StartupCommand
```

```powershell
Get-ItemProperty HKCU:\Software\Microsoft\Windows\CurrentVersion\Run
```

Linux defensive inspection can include:

```bash
systemctl list-units --type=service
```

```bash
systemctl list-timers
```

Activities focus on identifying:

- Services
- Scheduled tasks
- Startup applications
- Run keys
- Installed software
- Linux services
- Timers
- Persistence indicators

---

# 📡 COMMAND & CONTROL

Command & Control analysis focuses on network communication and unusual connection behavior.

Activities include:

- Active connections
- Listening ports
- DNS activity
- TLS inspection
- Routing
- Proxy configuration
- Socket inspection
- Owning-process identification

Examples:

```powershell
Get-NetTCPConnection
```

```cmd
netstat -ano
```

```bash
ss -tulpn
```

Blue Team workflows help identify unexpected outbound communication.

Purple Team activities can safely validate whether controlled network activity is visible to monitoring systems.

---

# 🎯 ACTIONS ON OBJECTIVES

The final Kill Chain stage focuses on identifying behavior involving sensitive resources and security objectives.

Activities include:

- File inspection
- ACL inspection
- Evidence hashing
- SMB share review
- Local administrator review
- Authentication-event analysis
- Canary-file validation
- Response validation

The objective is to determine whether security controls can detect activity affecting important organizational resources.

---

# 🟣 PURPLE TEAM VALIDATION

Purple Team functionality connects Red Team testing directly to Blue Team visibility.

```text
AUTHORIZED RED ACTION
        ↓
GENERATE EXPECTED TELEMETRY
        ↓
BLUE TEAM SEARCH
        ↓
EVENT OBSERVED?
     ↙       ↘
   YES        NO
    ↓          ↓
 VALIDATED   DETECTION GAP
    ↓          ↓
 ATT&CK      CREATE /
 COVERAGE    IMPROVE RULE
       \      /
        ↓    ↓
         RETEST
```

This allows HIVE SECURITY to answer an important operational question:

> **If this activity occurred in our environment, would we actually see it?**

---

# 🎯 MITRE ATT&CK + KILL CHAIN

The Kill Chain works alongside the HIVE SECURITY MITRE ATT&CK Coverage workspace.

Security activity can move from:

```text
KILL CHAIN PHASE
       ↓
RED TEAM VALIDATION
       ↓
ATT&CK TECHNIQUE
       ↓
BLUE TEAM TELEMETRY
       ↓
DETECTION RULE
       ↓
PURPLE TEAM TEST
       ↓
COVERAGE
```

Coverage can be classified as:

```text
OBSERVED
DETECTION EXISTS
TESTED
GAP
```

---

# 🌐 OSINT & INTELLIGENCE LAUNCHPAD

HIVE SECURITY includes an analyst launchpad for external intelligence and OSINT resources.

Resources include:

### OSINT Framework

Structured directory of OSINT tools and resources.

### Shodan

Internet-connected device and exposed-service research.

### Censys

Internet host, service, certificate, and web-property intelligence.

### VirusTotal

File, hash, URL, domain, and IP reputation research.

### AbuseIPDB

IP reputation and abuse intelligence.

### GreyNoise

Internet scanning and background-noise intelligence.

### urlscan.io

Website and URL investigation.

### SecurityTrails

DNS and domain intelligence.

### crt.sh

Certificate Transparency research.

### CISA KEV

Known Exploited Vulnerabilities catalog.

### MITRE ATT&CK

Adversary tactics and techniques knowledge base.

### Cyber Kill Chain

Reference material for the Cyber Kill Chain methodology.

External intelligence resources open separately so the active HIVE SECURITY investigation remains available.

---

# 🌎 GLOBAL THREAT ACTIVITY

Threat Activity combines external intelligence with HIVE SECURITY investigation workflows.

Indicators can be pivoted into:

```text
IOC
 ↓
IOC INTELLIGENCE
 ↓
OSINT / REPUTATION
 ↓
WATCHLIST
 ↓
INVESTIGATION
 ↓
ASSET CORRELATION
 ↓
FINDING
 ↓
REMEDIATION
```

Supported intelligence workflows include:

- CISA KEV
- Feodo
- DShield
- Spamhaus
- NVD
- ThreatFox
- GreyNoise
- AlienVault OTX
- AbuseIPDB
- VirusTotal

Some services require their own API credentials.

---

# 🔎 BUILT-IN PENTEST SCANNER

HIVE SECURITY includes a native authorized vulnerability-assessment scanner.

No separate Nessus or Nmap installation is required for its native scanning functionality.

### Quick

```text
Up to approximately /22
1,024 total IPv4 addresses
```

### Standard

```text
Up to approximately /24
256 total IPv4 addresses
```

### Credentialed

```text
Up to approximately /24
256 total IPv4 addresses
```

Capabilities include:

- TCP service discovery
- Common application ports
- HTTP inspection
- Security-header analysis
- TLS inspection
- Banner inspection
- Risky exposed-service checks
- Selected legacy service indicators
- SSH authenticated inventory
- Windows WinRM authenticated inventory
- PDF reports
- Finding import

---

# ⏱️ SCHEDULED SCANNING

Scans can be scheduled to run while HIVE SECURITY is operating.

Schedules can contain:

- Target
- Scan type
- Credential profile
- Schedule
- Previous run
- Result

Historical results help identify:

```text
NEW SERVICES
CLOSED SERVICES
NEW FINDINGS
REMEDIATED FINDINGS
CONFIGURATION CHANGES
```

---

# 🎯 EXPOSURE MANAGEMENT

Scanner findings can be correlated with CVE and CISA KEV intelligence.

```text
ASSET
  ↓
SERVICE
  ↓
VULNERABILITY
  ↓
CVE
  ↓
CISA KEV?
  ↓
PRIORITY
  ↓
REMEDIATE
  ↓
RETEST
```

---

# 🚨 SOC & INCIDENT RESPONSE

HIVE SECURITY uses a six-phase incident lifecycle:

```text
1. Detect & Validate
2. Scope & Preserve
3. Contain
4. Eradicate
5. Recover
6. Lessons Learned
```

Incidents can connect to investigations, evidence, findings, and other operational information.

---

# 🔒 EVIDENCE LOCKER

Evidence management includes:

- Encrypted file storage
- SHA-256 hashing
- Investigator
- Timestamp
- Investigation association
- Notes
- Audit events

Evidence file bytes are treated as immutable.

---

# 🛡️ STIG COMPLIANCE

Capabilities include:

- Windows security baseline assessment
- CKL import
- CKLB import
- XCCDF/XML import
- CAT I
- CAT II
- CAT III
- Scan history
- Finding status
- Remediation

The native HIVE SECURITY baseline scanner is a defensive helper and is not represented as a replacement for official DISA assessment tooling.

---

# 🤖 LOCAL AI

## Meta Llama 3.2 3B + Ollama

The **HIVE SECURITY 0.7.5 FULL INSTALL** includes Local AI provisioning.

The installer checks for:

```text
OLLAMA
   +
META LLAMA 3.2 3B
```

Installation workflow:

```text
Install HIVE SECURITY
        ↓
Check Ollama
    ↙       ↘
FOUND       MISSING
  ↓            ↓
REUSE       INSTALL
    \         /
        ↓
Check llama3.2:3b
    ↙           ↘
FOUND           MISSING
  ↓                ↓
REUSE           DOWNLOAD
     \            /
          ↓
     START OLLAMA
          ↓
     API HEALTH TEST
          ↓
     AI INFERENCE TEST
          ↓
     LOCAL AI READY
```

The Ollama API is accessed locally at:

```text
http://127.0.0.1:11434
```

A repair/provisioning utility is also included:

```bat
SETUP_LOCAL_AI.bat
```

---

# 📚 HIVE SECURITY ACADEMY

Integrated certification preparation includes:

### CompTIA Security+
- SY0-701-oriented
- 80 original questions

### CompTIA SecurityX
- CAS-005-oriented
- 80 original questions

### ISC2 CISSP
- 8 domains
- 80 original questions

### Linux Foundation LFCS
- Linux administration
- 80 original knowledge questions
- Hands-on labs

### EC-Council CEH
- v13-oriented
- 20 modules
- 80 original questions

The Academy includes:

- Guided lessons
- Practice exams
- Immediate answer feedback
- Correct-answer explanations
- Domain scoring
- Flashcards
- Labs
- Resource links
- PASS / NOT YET PASSING results

---

# 👥 USER MANAGEMENT

Portal roles include:

```text
ADMIN
ANALYST
VIEWER
```

Administrators can:

- Create users
- Edit users
- Disable users
- Delete users
- Reset passwords
- Manage certifications
- Manage scan credentials

Passwords are protected using Argon2 hashing.

---

# 🎓 PROFESSIONAL CERTIFICATIONS

User profiles can store certifications such as:

```text
CompTIA Security+
CompTIA SecurityX
ISC2 CISSP
Linux Foundation LFCS
EC-Council CEH
Other
```

Records can include:

- Credential ID
- Issue date
- Expiration date
- Verification URL
- Notes

Certification records support add, edit, and delete operations.

---

# 🔒 SECURITY ARCHITECTURE

HIVE SECURITY is designed as a local-first platform.

Security controls include:

- Loopback-only application service
- Authentication
- Argon2 password hashing
- Random session tokens
- Hashed session tokens
- HttpOnly cookies
- SameSite cookies
- CSRF protection
- Login rate limiting
- Host-header restrictions
- Security headers
- Role-based access control
- Encryption of sensitive fields
- Encrypted pentest reports
- Encrypted evidence
- Encrypted scanner credentials
- Encrypted integration secrets
- Audit logging

---

# 🪟 WINDOWS INSTALLATION

## Requirements

Recommended:

```text
Windows 10 / Windows 11
64-bit Windows
Internet connection for initial setup
Several GB of disk space for Local AI
```

## Install

1. Download:

```text
HIVE_SECURITY_0_7_5_FULL_INSTALL.zip
```

2. Extract the ZIP.

3. Run the included installation BAT file.

4. Allow the installer to provision dependencies and Local AI.

5. Launch HIVE SECURITY from the installed Windows shortcut/application.

---

# 🔄 UPGRADES & PERSISTENT DATA

HIVE SECURITY separates application code from persistent operational data.

Upgrades are designed to preserve existing:

- Users
- Password hashes
- Certifications
- API keys
- Integration secrets
- Scan credentials
- Findings
- Investigations
- Incidents
- Assets
- Risks
- Evidence
- Pentest reports
- Scan history
- STIG history
- Scheduled scans
- Detection rules
- Watchlists
- Academy progress
- Audit history

Backups are still recommended before major upgrades.

---

# ⚠️ AUTHORIZED USE ONLY

HIVE SECURITY is intended for legitimate:

- Defensive cybersecurity
- Security administration
- Vulnerability assessment
- Threat intelligence
- Incident response
- Detection engineering
- Compliance assessment
- Security education
- Security research
- Authorized penetration testing
- Red Team exercises
- Blue Team operations
- Purple Team validation

**Only scan, investigate, or test systems that you own or have explicit authorization to assess.**

The Interactive Kill Chain is designed as an authorized security-testing and defensive-validation reference.

It intentionally does not provide automated malware deployment, destructive exploitation, credential theft, persistence deployment, stealth/evasion, or uncontrolled attack automation.

---


```text
              GLOBAL SIGNALS
                    ↓
             THREAT ACTIVITY
                    ↓
             IOC INTELLIGENCE
                    ↓
          INTERACTIVE KILL CHAIN
                    ↓
       ┌────────────┼────────────┐
       ↓            ↓            ↓
    🔴 RED        🔵 BLUE      🟣 PURPLE
       └────────────┼────────────┘
                    ↓
               MITRE ATT&CK
                    ↓
          DETECTION ENGINEERING
                    ↓
              INVESTIGATION
                    ↓
               REMEDIATION
                    ↓
                  RETEST
                    ↓
                 ASSURE
```

### SIGNAL → INVESTIGATE → REMEDIATE → VALIDATE → ASSURE

**One operational picture. One security workspace. Local-first.**

**HIVE SECURITY**
