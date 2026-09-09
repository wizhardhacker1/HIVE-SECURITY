<img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/d1333dc6-9464-4897-9c1b-46d23cd50450" /> Buy me a Coffee- buymeacoffee.com/wizhardhacker1


<img width="430" height="86" alt="image" src="https://github.com/user-attachments/assets/db9e8003-ac37-434a-8015-0c5c0f3102d6" />
<br>





### Local-First Cybersecurity Operations, Threat Intelligence, Vulnerability Management, Compliance & Security Training

<img width="1888" height="923" alt="image" src="https://github.com/user-attachments/assets/8b9d2295-2fec-4c1d-a660-7bc67c8687ea" />


**HIVE SECURITY** is a Windows-focused, local-first cybersecurity operations platform that brings threat intelligence, vulnerability assessment, incident response, penetration testing, exposure management, compliance, detection engineering, security education, reporting, and local AI into a unified workspace.

> **SIGNAL → INVESTIGATE → REMEDIATE → VALIDATE → ASSURE**

HIVE SECURITY is designed to reduce tool fragmentation by connecting security information and operational workflows inside one application.

---

## 🛡️ Platform Overview

HIVE SECURITY provides a unified environment for:

- Security operations
- Global threat intelligence
- IOC investigation
- Cybersecurity news
- Vulnerability scanning
- Credentialed security assessments
- Asset intelligence
- CVE and CISA KEV correlation
- Exposure management
- Incident response
- Investigations
- Evidence management
- Penetration-test reporting
- Remediation tracking
- STIG compliance
- Red Team operations
- Blue Team operations
- Purple Team validation
- Detection engineering
- MITRE ATT&CK coverage
- Risk and GRC
- Watchlists
- Scheduled scanning
- Executive reporting
- Security certification training
- Local AI

---

# 🖥️ UNIFIED OPERATIONS

The **Unified Operations** dashboard provides a single operational picture across HIVE SECURITY.

Instead of working through disconnected security tools, information moves through a common workflow:

```text
1. SIGNAL
   Threat Intelligence / Telemetry
              ↓
2. INVESTIGATE
   SOC / Investigations / Evidence
              ↓
3. REMEDIATE
   Vulnerabilities / STIG / Findings
              ↓
4. VALIDATE
   Red Team / Blue Team / Purple Team
              ↓
5. ASSURE
   Risk / Compliance / Reporting
```

The dashboard provides visibility into:

- Active incidents
- Investigations
- Open vulnerabilities
- Tracked findings
- STIG findings
- CAT I / II / III findings
- Integration health
- Active work
- Remediation activity

---

# 🌎 GLOBAL THREAT ACTIVITY

HIVE SECURITY aggregates threat intelligence to provide analysts with current IOC activity and security context.

Supported capabilities include:

- Malicious IP intelligence
- Threat-feed aggregation
- Recent IOC activity
- CISA Known Exploited Vulnerabilities
- Botnet intelligence
- Suspicious network indicators
- Threat investigation pivots
- IOC watchlists
- Threat-feed health

IOC results can be investigated directly using:

- HIVE SECURITY IOC Triage
- VirusTotal
- AbuseIPDB
- GreyNoise
- Shodan

Indicators can then move into investigations, findings, watchlists, or other operational workflows.

> Threat-feed indicators represent intelligence and should not automatically be interpreted as proof that an environment has been compromised.

---

# 🧠 IOC INTELLIGENCE CENTER

The IOC Intelligence Center provides centralized investigation of:

```text
IP Addresses
Domains
URLs
File Hashes
CVEs
```

Indicators can be:

- Enriched
- Investigated
- Added to watchlists
- Associated with investigations
- Connected to assets
- Connected to findings
- Marked benign
- Correlated with threat intelligence

Optional integrations can provide additional enrichment.

---

# 📰 CYBER NEWS

HIVE SECURITY includes an integrated cybersecurity news workspace.

Sources can include:

- BleepingComputer
- The Hacker News
- Dark Reading
- SecurityWeek
- Cybersecurity Dive
- CyberScoop
- The Record
- Krebs on Security
- CISA Cybersecurity Advisories

Features include:

- Headline aggregation
- Source filtering
- Search
- Publication dates
- Feed-health monitoring
- Original article links
- Government advisory identification

HIVE SECURITY links users to the original publishers rather than presenting third-party reporting as its own content.

---

# 🔎 BUILT-IN PENTEST SCANNER

HIVE SECURITY contains a built-in vulnerability-assessment scanner.

No separate Nessus or Nmap installation is required for the native scanning functionality.

## Scan Profiles

### Quick Scan

Designed for rapid host and common-service discovery.

Supports networks up to approximately:

```text
/22
1,024 total IPv4 addresses
```

### Standard Vulnerability Scan

Provides deeper inspection including:

- TCP service discovery
- Common service ports
- Management ports
- Database ports
- Web services
- HTTP analysis
- Security-header inspection
- TLS inspection
- Banner collection
- Exposed-service checks
- Selected version/configuration indicators

Supports networks up to approximately:

```text
/24
256 total IPv4 addresses
```

### Credentialed Scan

Supports authenticated assessment using stored credentials.

Credentialed scans support approximately:

```text
/24
256 total IPv4 addresses
```

---

# 🔐 SCAN CREDENTIALS

HIVE SECURITY supports encrypted credential profiles for authorized authenticated assessments.

## Linux / Unix

Supported credential information includes:

```text
SSH Username
Password
Private Key
```

## Windows

Supported credential information includes:

```text
WinRM Username
Password
Windows Domain
```

Sensitive credentials are encrypted at rest.

Stored passwords and private keys are not returned to the browser after they are saved.

Analysts are restricted according to their assigned permissions and credential profiles.

---

# 🎯 EXPOSURE MANAGEMENT

Exposure Management connects discovered infrastructure with vulnerability intelligence.

```text
ASSETS
   ↓
HIVE SECURITY SCANNER
   ↓
SERVICE DISCOVERY
   ↓
CVE / CISA KEV INTELLIGENCE
   ↓
POSSIBLE EXPOSURE
   ↓
VALIDATE FINDING
   ↓
OWNER + REMEDIATION
   ↓
RETEST
   ↓
VERIFIED REMEDIATED
```

This allows analysts to focus on vulnerabilities that may actually affect systems in their environment.

---

# 🖥️ ASSET INTELLIGENCE

HIVE SECURITY maintains persistent asset information.

Asset records can include:

- IP address
- Hostname
- Operating-system information
- Open ports
- Services
- Last scan
- Scan history
- Vulnerabilities
- Findings
- Incidents
- Owner
- Criticality
- Tags
- Exposure information

Assets connect scanning, investigations, findings, CVEs, remediation, and exposure management.

---

# 🧬 CVE & CISA KEV CORRELATION

HIVE SECURITY can correlate vulnerability information with known security intelligence.

Sources can include:

- NVD
- CISA Known Exploited Vulnerabilities
- HIVE SECURITY scanner results

The platform can help connect:

```text
Asset
  ↓
Service
  ↓
Possible CVE
  ↓
CISA KEV Status
  ↓
Finding
  ↓
Remediation
  ↓
Retest
```

CVE correlation is intended to assist analyst investigation and should be validated before being treated as a confirmed vulnerability.

---

# ⏱️ SCHEDULED SCANNING

Administrators can create recurring vulnerability-assessment jobs.

Scheduled scans can include:

- Target
- Scan profile
- Credential profile
- Schedule
- Previous result
- Last-run status

Historical scans can help identify changes such as:

```text
NEW SERVICE
CLOSED SERVICE
NEW FINDING
REMEDIATED FINDING
CONFIGURATION CHANGE
```

---

# 🚨 SOC / INCIDENT RESPONSE

HIVE SECURITY provides an incident-response workflow built around six phases:

```text
1. Detect & Validate
2. Scope & Preserve
3. Contain
4. Eradicate
5. Recover
6. Lessons Learned
```

Incident records can contain:

- Status
- Severity
- Owner
- Notes
- Evidence
- Lifecycle progress
- Related investigation information

---

# 🕵️ INVESTIGATIONS

Investigation case management provides a centralized location for security investigations.

Cases can contain:

- Investigation title
- Severity
- Status
- Summary
- IOCs
- Evidence
- Timeline information
- Notes
- Related assets
- Related incidents
- Related findings

User-created investigations can be edited or deleted according to permissions.

Important changes are captured through the audit system.

---

# 🔒 EVIDENCE LOCKER

HIVE SECURITY includes encrypted evidence management.

Evidence records can contain:

- Original filename
- SHA-256 hash
- Investigator
- Timestamp
- Case association
- Notes
- Audit history

Evidence files are encrypted at rest.

Evidence bytes are treated as immutable.

If evidence changes, a new evidence object should be stored instead of silently modifying the original file.

---

# 📄 PENTEST REPORT MANAGEMENT

Third-party penetration-test reports can be imported into HIVE SECURITY.

Supported formats include:

```text
PDF
DOCX
TXT
MD
CSV
JSON
XML
HTML
```

Features include:

- Encrypted report storage
- Extracted finding management
- Local AI-assisted analysis
- Manual finding creation
- Finding editing
- Finding deletion
- Severity tracking
- Evidence tracking
- Remediation recommendations
- Retesting
- Finding status
- PDF remediation reports

Deleting a pentest report can also remove report-derived findings and associated remediation documents.

Uploaded report content is treated as data and is not executed.

---

# 🤖 LOCAL AI

## Meta Llama 3.2 3B + Ollama

HIVE SECURITY integrates a local AI system using:

```text
Ollama
+
Meta Llama 3.2 3B
```

The installer can automatically:

1. Check for Ollama
2. Reuse an existing installation
3. Install Ollama when missing
4. Check for `llama3.2:3b`
5. Download the model when missing
6. Start/check the local Ollama service
7. Verify the local API
8. Perform a real inference health test

The local AI API uses:

```text
http://127.0.0.1:11434
```

This allows supported AI workflows to remain on the local system instead of requiring report content to be sent to a cloud LLM.

A separate repair utility is also provided:

```text
SETUP_LOCAL_AI.bat
```

---

# 🛠️ REMEDIATION QUEUE

Security findings can be managed through a centralized remediation workflow.

Typical states include:

```text
OPEN
IN PROGRESS
AWAITING RETEST
REMEDIATED
ACCEPTED RISK
CLOSED
```

Records can include:

- Finding
- Severity
- Owner
- Due date
- SLA
- Evidence
- Remediation
- Retest result
- Current status

---

# 🛡️ STIG COMPLIANCE

HIVE SECURITY includes Windows defensive-baseline assessment capabilities and support for imported STIG assessment results.

Supported imports include:

```text
CKL
CKLB
XCCDF
XML
```

Capabilities include:

- Windows baseline checks
- CAT I tracking
- CAT II tracking
- CAT III tracking
- Scan history
- Finding status
- Remediation tracking
- Imported assessment management

### Important

The native HIVE SECURITY baseline scanner is a defensive configuration-assessment helper.

It is **not a replacement for official DISA STIG assessment tooling**.

Organizations requiring authoritative STIG assessments should use applicable DISA benchmarks and approved assessment tools.

---

# ⚔️ RED TEAM

The Red Team workspace provides authorized security-testing references and engagement tracking.

Capabilities focus on areas such as:

- Reconnaissance
- DNS inspection
- HTTP inspection
- TLS inspection
- Service discovery
- Local posture checks
- Evidence collection
- Engagement tracking

HIVE SECURITY does not provide automated malware deployment, destructive attacks, persistence, credential theft, or security-control evasion.

---

# 🔵 BLUE TEAM

The Blue Team workspace provides defensive investigation and response resources.

Areas include:

- IOC analysis
- Log investigation
- Host investigation
- Network investigation
- Evidence collection
- Detection
- Incident response
- Defensive command references

---

# 🟣 PURPLE TEAM

Purple Team connects offensive validation with defensive detection.

Analysts can use Purple Team workflows to:

- Validate detections
- Record test results
- Identify security gaps
- Associate MITRE ATT&CK techniques
- Improve defensive coverage
- Connect Red Team activity to Blue Team visibility

---

# 🎯 MITRE ATT&CK COVERAGE

HIVE SECURITY can map security activity against MITRE ATT&CK.

Mappings can connect:

- Investigations
- Findings
- Threat intelligence
- Detection rules
- Purple Team tests

Coverage states can include:

```text
OBSERVED
DETECTION EXISTS
TESTED
GAP
```

This provides a view of where security visibility and validation exist and where additional defensive work may be needed.

---

# 📡 DETECTION ENGINEERING

HIVE SECURITY includes a defensive detection library.

Supported detection content can include:

```text
Sigma
YARA
Splunk
Microsoft KQL
Elastic
```

Detection records can be connected to:

- MITRE ATT&CK
- Investigations
- Threat intelligence
- Purple Team validation
- Security findings

---

# 👁️ WATCHLISTS

Watchlists allow analysts to monitor security objects of interest.

Supported watchlist objects can include:

```text
IP Address
Domain
Hash
CVE
Vendor
Product
Asset
```

HIVE SECURITY can correlate watchlist entries against supported:

- Threat intelligence
- CISA KEV
- Cyber News
- Scanner results
- Investigations

---

# 🔔 NOTIFICATIONS

Notification rules can surface important security events.

Examples include:

- Critical finding
- CISA KEV exposure
- Scan completed
- Scan failed
- Credential failure
- Finding overdue
- Certificate issue
- Watchlist match
- Important threat activity

---

# 📊 EXECUTIVE REPORTING

HIVE SECURITY can generate security reporting covering areas such as:

- Vulnerability posture
- Critical findings
- Remediation progress
- Incident activity
- Scan coverage
- STIG posture
- KEV exposure
- Risk posture
- Security trends

PDF reports can be used for operational review and management reporting.

---

# 📋 RISK & GRC

Framework tracking includes:

- NIST Cybersecurity Framework 2.0
- CIS Controls v8
- ISO/IEC 27001
- NIST RMF / SP 800-53
- PCI DSS
- SOC 2
- HIPAA Security Rule

Risk records can be tracked alongside operational security findings.

---

# 📚 HIVE SECURITY ACADEMY

HIVE SECURITY contains an integrated cybersecurity certification training environment.

---

## CompTIA Security+

SY0-701-oriented training includes:

- 80 original practice questions
- Guided modules
- Flashcards
- Labs
- Video resources
- Official resources

Major study areas include:

- Security concepts
- Threats and vulnerabilities
- Security architecture
- Security operations
- Security program management

---

## CompTIA SecurityX

CAS-005-oriented training includes:

- 80 original practice questions
- Guided modules
- Flashcards
- Labs
- Video and official resources

Study areas include:

- Governance, Risk and Compliance
- Security Architecture
- Security Engineering
- Security Operations
- Zero Trust
- Cloud security
- OT/ICS
- Detection engineering
- Incident response

---

## CISSP

CISSP preparation covers all eight major domains:

1. Security and Risk Management
2. Asset Security
3. Security Architecture and Engineering
4. Communication and Network Security
5. Identity and Access Management
6. Security Assessment and Testing
7. Security Operations
8. Software Development Security

Includes:

- 80 original practice questions
- Guided modules
- Flashcards
- Labs
- Official learning resources

---

## LFCS

Linux Foundation Certified System Administrator preparation covers:

- Operations & Deployment
- Networking
- Storage
- Essential Commands
- Users & Groups

Includes:

- 80 original knowledge questions
- Guided modules
- Flashcards
- Hands-on labs
- Official learning resources

LFCS is performance-based, so HIVE SECURITY's multiple-choice testing is intended as supporting knowledge preparation rather than a reproduction of the actual certification exam.

---

## CEH

CEH v13-oriented preparation includes:

- 20 guided modules
- 80 original questions
- Flashcards
- Labs
- Video resources
- Official resources

---

# 📝 INTERACTIVE EXAMS

Academy tests can be configured as:

```text
10 Questions
25 Questions
40 Questions
Full Question Bank
```

After answering a question, HIVE SECURITY immediately provides:

```text
CORRECT
or
INCORRECT
```

along with:

- Correct answer
- Explanation
- Domain information

Once the answer has been revealed, the recorded response cannot be changed.

At completion, the test displays:

- Correct answers
- Incorrect answers
- Unanswered questions
- Percentage
- Domain performance
- PASS / NOT YET PASSING
- Complete answer review

Practice scoring is clearly distinguished from vendor-specific scaled or performance-based certification scoring.

---

# 🎓 USER CERTIFICATION PROFILES

Administrators can associate professional certifications with portal users.

Supported credential types include:

```text
Security+
SecurityX
CISSP
LFCS
CEH
Other
```

Certification records can contain:

- Certification name
- Credential / certificate ID
- Issue date
- Expiration date
- Verification URL
- Notes

Certification records can be:

```text
ADD
EDIT
DELETE
```

---

# 👥 PORTAL USER MANAGEMENT

HIVE SECURITY supports role-based user accounts.

## Administrator

Full administrative and configuration access.

## Analyst

Operational security access according to assigned permissions.

## Viewer

Read-only access to supported areas.

Administrators can:

- Create users
- Edit users
- Delete users
- Enable users
- Disable users
- Change portal passwords
- Manage professional certifications
- Manage scanner credential profiles

Changing a user's password revokes that user's existing sessions.

Portal passwords are protected using Argon2 password hashing.

---

# 🧰 SECURITY OPERATIONS TOOLBOX

The built-in analyst toolbox includes utilities such as:

- Hash generation
- IOC parsing
- Base64 encoding/decoding
- URL encoding/decoding
- Hex utilities
- Subnet calculations
- JWT decoding
- Regex testing
- SIEM query generation
- Password generation
- Password-hash auditing

The password-hash audit capability is deliberately bounded.

It is intended only for password hashes that the operator owns or is explicitly authorized to assess.

It does not perform remote password spraying.

---

# 🔌 INTEGRATIONS

HIVE SECURITY supports public intelligence sources and optional API-based integrations.

## No-Key / Public Sources

Examples include:

- CISA KEV
- Feodo Tracker
- DShield
- Spamhaus DROP
- NVD

## Optional Intelligence Integrations

Examples include:

- ThreatFox
- GreyNoise
- AlienVault OTX
- AbuseIPDB
- VirusTotal

HIVE SECURITY can also maintain configuration for security operations integrations such as SIEM, XDR, cloud, ticketing, and notification systems.

Sensitive integration secrets are encrypted.

---

# ✏️ DATA MANAGEMENT

A core HIVE SECURITY design rule is:

> **Operational information created by a user should be manageable by that user or an authorized administrator.**

Where appropriate, user-created records support:

```text
VIEW
EDIT
DELETE
EXPORT
```

This applies across areas such as:

- Investigations
- Incidents
- Assets
- Risks
- Findings
- Pentest reports
- Scanner results
- STIG scans
- Scheduled scans
- Watchlists
- Detection rules
- Evidence notes
- Notification rules
- User certifications
- Playbook activity

Security-sensitive actions are audit logged.

Deleting an operational object does not require removing the minimal security audit record documenting who performed the deletion and when.

---

# 📜 AUDIT LOGGING

Security-sensitive actions are recorded in the HIVE SECURITY audit system.

Audit information can include:

- User
- Action
- Source IP
- Timestamp
- Object affected
- Security event type

Examples include:

- Authentication failure
- Blocked authentication
- User creation
- User deletion
- Password reset
- Credential modification
- Finding deletion
- Evidence activity
- Scan activity
- Configuration changes

Sensitive passwords and private keys are not written to the audit log.

---

# 🔒 SECURITY ARCHITECTURE

HIVE SECURITY is designed as a local-first application.

Security controls include:

- Loopback-only application binding
- Authentication
- Argon2 password hashing
- Random session tokens
- Hashed session-token storage
- HttpOnly session cookies
- SameSite cookies
- CSRF protection
- Login rate limiting
- Host-header restrictions
- Security headers
- Role-based access control
- Encrypted sensitive fields
- Encrypted pentest reports
- Encrypted evidence
- Encrypted scan credentials
- Encrypted integration secrets
- Audit logging

For additional host protection, Windows device encryption or BitLocker is recommended where appropriate.

---

# 🪟 WINDOWS INSTALLATION

## Requirements

Recommended:

```text
Windows 10 / Windows 11
64-bit Windows
Internet connection for initial dependency/model installation
Several GB of available disk space for Local AI
```

---

## Installation

### 1. Download HIVE SECURITY

Download the latest:

```text
HIVE_SECURITY_FULL_INSTALL.zip
```

### 2. Extract the ZIP

Do not run the installer directly from inside the compressed archive.

### 3. Run

```bat
INSTALL_HIVE_SECURITY.bat
```

The installer provisions the application and its required local environment.

---

# 🤖 LOCAL AI INSTALLATION

During installation, HIVE SECURITY checks for Ollama.

```text
Ollama installed?
       │
       ├── YES → reuse installation
       │
       └── NO → install Ollama
                       ↓
              Check llama3.2:3b
                       ↓
               Model installed?
                 │           │
                YES          NO
                 │           │
                 └─────→ Download
                            ↓
                     Start Ollama
                            ↓
                     API Health Check
                            ↓
                     Inference Test
                            ↓
                     LOCAL AI READY
```

If Local AI requires repair or reprovisioning, run:

```bat
SETUP_LOCAL_AI.bat
```

---

# 🚀 APPLICATION LAUNCHER

Normal day-to-day use should be through:

```text
HiveSecurity.exe
```

The launcher:

1. Starts the secured local backend
2. Waits for the application to become healthy
3. Opens the HIVE SECURITY portal
4. Uses the branded HIVE SECURITY Windows icon

The application uses a local web interface rather than exposing the service publicly.

---

# 📁 APPLICATION STORAGE

The intended HIVE SECURITY installation structure is:

```text
%LOCALAPPDATA%\HiveSecurity\
│
├── HiveSecurity.exe
│
├── app\
├── data\
├── logs\
└── backups\
```

Persistent operational information belongs under:

```text
%LOCALAPPDATA%\HiveSecurity\data
```

Application code and persistent data are separated so application upgrades do not intentionally replace the operational database.

---

# 🔄 UPGRADING

New HIVE SECURITY versions are designed to preserve existing operational data.

This can include:

- Portal users
- Password hashes
- User certifications
- Scan credentials
- API keys
- Integration secrets
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
- Study progress
- Audit history

Database migrations are performed when application schemas change.

Backups are still recommended before significant upgrades.

---

# 🔐 PRIVACY

HIVE SECURITY is designed around local operation.

Operational data is stored on the user's computer.

Sensitive information can be encrypted locally, including:

- Pentest reports
- Evidence
- Scan credentials
- Integration secrets
- Sensitive finding content

Local AI communicates with Ollama over the loopback interface:

```text
127.0.0.1
```

External intelligence and news services necessarily receive normal network requests when those services are accessed.

---

# ⚠️ AUTHORIZED USE ONLY

HIVE SECURITY is intended for legitimate:

- Cybersecurity operations
- Defensive security
- System administration
- Threat intelligence
- Vulnerability assessment
- Incident response
- Compliance assessment
- Security education
- Security research
- Authorized penetration testing

**Only scan, assess, monitor, or test systems that you own or have explicit authorization to evaluate.**

Users are responsible for complying with applicable:

- Laws
- Regulations
- Contracts
- Organizational policies
- Rules of engagement
- Authorization boundaries

---

# ⚠️ DISCLAIMER

HIVE SECURITY is a security operations and assessment platform.

Automated findings, CVE correlations, service identification, threat-intelligence matches, Local AI analysis, and other automated results should be validated by a qualified analyst before operational decisions are made.

HIVE SECURITY does not claim to replace authoritative commercial or government-required security assessment products where those products are mandated.

---

# 🛡️ HIVE SECURITY

```text
               SIGNAL
                  ↓
             INVESTIGATE
                  ↓
              REMEDIATE
                  ↓
               VALIDATE
                  ↓
                ASSURE
```

### One operational picture. One security workspace. Local-first.

**HIVE SECURITY**
