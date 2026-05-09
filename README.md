# 📋 GRC Capstone — Risk Assessment, Treatment Plan & Security Policies | SecureEdge Ltd

<div align="center">

![ISO 27001](https://img.shields.io/badge/Framework-ISO_27001:2022-0052CC?style=for-the-badge&logoColor=white)
![NIST](https://img.shields.io/badge/Framework-NIST_CSF-004B87?style=for-the-badge&logoColor=white)
![GRC](https://img.shields.io/badge/Type-GRC_Assessment-FF8C00?style=for-the-badge&logoColor=white)
![Nmap](https://img.shields.io/badge/Tool-Nmap_Scan-4EAA25?style=for-the-badge&logoColor=white)
![CVSS](https://img.shields.io/badge/Scoring-CVSS_v3.1-CC0000?style=for-the-badge&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)
![Classification](https://img.shields.io/badge/Classification-Confidential-red?style=for-the-badge)

**A comprehensive Governance, Risk & Compliance (GRC) capstone project for SecureEdge Ltd — covering penetration testing, NMAP network scanning, ISO 27001 internal audit, risk register construction, 5×5 risk matrix scoring, and full security policy development including a Penetration Testing Policy and Vulnerability Management Policy.**

[📋 Summary](#-executive-summary) • [🔍 NMAP Scan](#-nmap-scan-results) • [⚠️ Risk Register](#️-risk-register) • [✅ ISO Audit](#-iso-27001-internal-audit-checklist) • [📜 Policies](#-security-policies)

</div>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Document Information](#-document-information)
- [Workbook Structure](#-workbook-structure)
- [Executive Summary](#-executive-summary)
- [NMAP Scan Results](#-nmap-scan-results)
- [Risk Register](#️-risk-register)
- [Risk Matrix](#-risk-matrix)
- [ISO 27001 Internal Audit Checklist](#-iso-27001-internal-audit-checklist)
- [Security Policies](#-security-policies)
  - [Penetration Testing Policy](#1-penetration-testing-policy)
  - [Vulnerability Management Policy](#2-vulnerability-management-policy)
- [Key Findings Summary](#-key-findings-summary)
- [Frameworks & Compliance](#-frameworks--compliance)
- [Tools Used](#️-tools-used)
- [Team](#-team)
- [Author](#-author)

---

## 🔭 Project Overview

SecureEdge Ltd engaged a GRC analyst team to conduct its **first full penetration test and risk assessment** as part of preparing for **ISO 27001 certification**. The test revealed a combination of technical and governance weaknesses posing material business risk that must be addressed before certification.

This capstone delivers a complete, structured GRC package including:

- ✅ **NMAP network reconnaissance** — real scan output with 10+ open ports identified
- ✅ **Risk register** — structured risk identification, scoring, and treatment planning
- ✅ **5×5 Risk matrix** — likelihood × impact heat map
- ✅ **ISO 27001:2022 internal audit** — clause-by-clause compliance evaluation
- ✅ **Penetration Testing Policy** — formal organizational policy
- ✅ **Vulnerability Management Policy** — remediation timelines and program governance

---

## 📄 Document Information

| Field | Value |
|-------|-------|
| **Document Title** | Risk Assessment and Treatment Plan |
| **Version** | 1.0 |
| **Group** | Group 2 — NA |
| **Document Authors** | Philip Ufuah, Emmanuel Aderogba, Justice Alucho, Omotayo Ogunnika, Davidmarie Okon |
| **Document Owner** | Group 2 — Chief Information Security Officers |
| **Classification** | Confidential |
| **Date Signed Off** | 24/11/2025 |
| **Organization** | SecureEdge Ltd |
| **Purpose** | ISO 27001 Certification Preparation |

---

## 🗂️ Workbook Structure

| Sheet | Title | Contents |
|-------|-------|---------|
| Sheet 1 | **Cover Page** | Document metadata, version control, classification, table of contents |
| Sheet 2 | **Executive Summary** | Business risk overview, key findings, leadership narrative |
| Sheet 3 | **Risk Register** | Full risk register — IDs, threat sources, vulnerabilities, scores |
| Sheet 4 | **NMAP Scan Result** | Real network reconnaissance output — open ports and services |
| Sheet 5 | **ISO 27001 Internal Audit Checklist** | Clause-by-clause compliance audit |
| Sheet 6 | **Risk Matrix** | 5×5 likelihood × impact heat map |

---

## 📸 Screenshots

### Figure 1 — Cover Page
> *Risk Assessment and Treatment Plan v1.0 — Document Author: Group 2 — NA — Risk Analysts. Document Owner: Group 2 — CISOs. Classification: Confidential. Date Signed Off: 24/11/2025.*

📸 `screenshots/01_cover_page.png`

---

### Figure 2 — Executive Summary
> *SecureEdge Ltd's first full penetration test summary — Key risks: Weak SSH credentials (brute-force, data loss, system takeover) and Unpatched operating systems with known CVEs (RCE, ISO 27001 non-compliance, reputational damage).*

📸 `screenshots/02_executive_summary.png`

---

### Figure 3 — Risk Register (R-001)
> *Risk Register showing R-001: Identity & Access Management. Affected assets: Production Linux servers. Threat source: External attackers — credential brute force / automated bots. Vulnerability: Weak SSH credentials / password reuse. Existing controls: SSH on standard port, basic firewall rate-limiting, login auditing. Likelihood: 4 | Impact: 4 | Score: 16 — HIGH.*

📸 `screenshots/03_risk_register.png`

---

### Figure 4 — NMAP Scan Results
> *Real NMAP scan of host 10.0.2.4 showing 10 open TCP ports including dangerous services: FTP (21), SSH (22), Telnet (23), SMTP (25), DNS (53), HTTP (80), RPC (111), Samba (139/445), exec (512). All services identified with version numbers.*

📸 `screenshots/04_nmap_scan.png`

---

### Figure 5 — ISO 27001 Internal Audit Checklist
> *ISO 27001 Internal Audit Checklist — Section [1] Governance & Scope (Clause 4 & 6). Items 1.1 (penetration testing in ISMS scope), 1.2 (vulnerability management in ISMS boundaries), and 1.3 (risks related to pentesting in risk assessment) — all marked Compliant: Y with evidence references.*

📸 `screenshots/05_iso_audit_checklist.png`

---

## 📋 Executive Summary

SecureEdge Ltd completed its first full penetration test as part of ISO 27001 preparation. The test revealed a combination of **technical and governance weaknesses** that pose a material business risk and must be addressed before certification.

### Key Risks & Business Impact

#### 🔴 Risk 1 — Weak SSH Credentials on Production Servers

| Field | Detail |
|-------|--------|
| **Risk** | Brute-force compromise, unauthorized access, data loss, system takeover, service outages |
| **Business Impact** | Operational disruption, lost customer trust, revenue decline |
| **Validated By** | NMAP scan — SSH (Port 22) open: OpenSSH 4.7p1 Debian 8ubuntu1 |

#### 🔴 Risk 2 — Unpatched Operating Systems (Known CVEs)

| Field | Detail |
|-------|--------|
| **Risk** | Remote code execution, data breaches, service disruption |
| **Business Impact** | ISO 27001 non-compliance, remediation costs, reputational damage |
| **Validated By** | NMAP — Apache 2.2.8, vsftpd 2.3.4, OpenSSH 4.7p1 (all outdated) |

#### 🟠 Risk 3 — Unnecessary Open Services (Telnet, FTP, rexecd)

| Field | Detail |
|-------|--------|
| **Risk** | Plaintext credential exposure, lateral movement, unauthorized remote execution |
| **Business Impact** | Data interception, compliance violation, operational risk |
| **Validated By** | NMAP — Port 23 (Telnet), Port 21 (FTP), Port 512 (exec/rexecd) |

---

## 🔍 NMAP Scan Results

Real network reconnaissance was performed using **NMAP** against host `10.0.2.4`. The scan identified **10+ open TCP ports** with detailed service version fingerprinting.

### Raw NMAP Output

```
host          port   proto  name          state  info
──────────────────────────────────────────────────────────────────────────────
10.0.2.4      21     tcp    ftp           open   vsftpd 2.3.4
10.0.2.4      22     tcp    ssh           open   OpenSSH 4.7p1 Debian 8ubuntu1 protocol 2.0
10.0.2.4      23     tcp    telnet        open   Linux telnetd
10.0.2.4      25     tcp    smtp          open   Postfix smtpd
10.0.2.4      53     tcp    domain        open   ISC BIND 9.4.2
10.0.2.4      80     tcp    http          open   Apache httpd 2.2.8 (Ubuntu) DAV/2
10.0.2.4      111    tcp    rpcbind       open   2 RPC #100000
10.0.2.4      139    tcp    netbios-ssn   open   Samba smbd 3.X - 4.X workgroup: WORKGROUP
10.0.2.4      445    tcp    netbios-ssn   open   Samba smbd 3.0.20-Debian workgroup: WORKGROUP
10.0.2.4      512    tcp    exec          open   netkit-rsh rexecd
```

---

### Risk Assessment — Per Open Port

| Port | Service | Version | Risk Level | Finding |
|------|---------|---------|------------|---------|
| **21** | FTP | vsftpd 2.3.4 | 🔴 **CRITICAL** | vsftpd 2.3.4 contains a **backdoor vulnerability (CVE-2011-2523)** — remote shell access via malformed username |
| **22** | SSH | OpenSSH 4.7p1 Debian | 🟠 **HIGH** | Severely outdated version (2008). Multiple known CVEs. Password auth enabled enabling brute-force |
| **23** | Telnet | Linux telnetd | 🔴 **CRITICAL** | Unencrypted plaintext protocol. Credentials transmitted in clear — **should be disabled immediately** |
| **25** | SMTP | Postfix smtpd | 🟡 **MEDIUM** | Mail relay misconfiguration risk. Potential for spam relay abuse if not restricted |
| **53** | DNS | ISC BIND 9.4.2 | 🟠 **HIGH** | BIND 9.4.2 is EOL with critical vulnerabilities including zone transfer and cache poisoning |
| **80** | HTTP | Apache 2.2.8 Ubuntu | 🟠 **HIGH** | Apache 2.2.8 (2008) — multiple critical CVEs including mod_rewrite, mod_proxy, and DoS vulnerabilities |
| **111** | RPC | rpcbind 2 | 🟡 **MEDIUM** | RPC portmapper — enables enumeration of running RPC services; attack surface expansion |
| **139** | Samba | smbd 3.X–4.X | 🟠 **HIGH** | Samba 3.x contains multiple known vulnerabilities including remote code execution |
| **445** | Samba | smbd 3.0.20-Debian | 🔴 **CRITICAL** | Samba 3.0.20 — vulnerable to **MS-17-010 style exploitation** and authentication bypass |
| **512** | exec | netkit-rsh rexecd | 🔴 **CRITICAL** | Remote execution daemon — allows unauthenticated remote command execution. **Immediate shutdown required** |

### Nmap Command Used

```bash
# Service version detection scan
nmap -sV -p- 10.0.2.4

# OS detection and script scanning
nmap -A -O 10.0.2.4

# Output to file for documentation
nmap -sV -oN nmap_scan_results.txt 10.0.2.4
```

### Critical NMAP Findings Summary

```
🔴 CRITICAL FINDINGS (Disable Immediately):
├── Port 21  — vsftpd 2.3.4 BACKDOOR (CVE-2011-2523)
├── Port 23  — Telnet running (plaintext credentials)
├── Port 445 — Samba 3.0.20 (RCE vulnerable)
└── Port 512 — rexecd running (unauthenticated remote exec)

🟠 HIGH FINDINGS (Patch Urgently):
├── Port 22  — OpenSSH 4.7p1 (severely outdated, brute-force risk)
├── Port 53  — BIND 9.4.2 (EOL, multiple critical CVEs)
├── Port 80  — Apache 2.2.8 (EOL, RCE vulnerabilities)
└── Port 139 — Samba 3.x (authentication bypass CVEs)

🟡 MEDIUM FINDINGS (Harden):
├── Port 25  — SMTP relay misconfiguration risk
└── Port 111 — RPC portmapper (attack surface enumeration)
```

---

## ⚠️ Risk Register

### Register Schema

| Column | Description |
|--------|-------------|
| **Risk ID** | Unique identifier (R-001, R-002...) |
| **Risk Statement** | Full narrative of the risk scenario and potential consequences |
| **Category** | Risk domain (Identity & Access Management, Network Security, etc.) |
| **Affected Assets** | Systems, data, or processes exposed |
| **Threat Source** | Origin (external attacker, insider, natural event, automated bot) |
| **Vulnerability** | Specific technical weakness being exploited |
| **Existing Controls** | Current mitigations already in place |
| **Likelihood (1–5)** | Probability of occurrence |
| **Impact (1–5)** | Severity of business impact if risk materializes |
| **Risk Score** | Likelihood × Impact (max 25) |
| **Risk Level** | Critical / High / Medium / Low |
| **Treatment** | Accept / Mitigate / Transfer / Avoid |
| **Treatment Action** | Specific remediation steps assigned |
| **Owner** | Responsible party |
| **Due Date** | Remediation deadline |
| **Residual Risk** | Risk score after treatment applied |

---

### Key Risk Entries

#### R-001 — Weak SSH Credentials (Identity & Access Management)

```
Risk Statement:   Weak credentials on production servers risk brute-force
                  compromise, leading to unauthorized access, data loss,
                  system takeover, and service outages

Category:         Identity & Access Management
Affected Assets:  Production Linux servers (SSH-accessible hosts)
Threat Source:    External attackers — credential brute force, automated bots
Vulnerability:    Weak SSH credentials / password reuse / password-only auth

Existing Controls:
  ├── SSH service running on standard port (Port 22)
  ├── Basic rate-limiting on firewall for some hosts
  └── Login auditing enabled

Likelihood:   4 / 5
Impact:       4 / 5
Risk Score:   16 / 25   →  🟠 HIGH
Treatment:    MITIGATE
```

**Treatment Actions for R-001:**

```bash
# 1. Disable password authentication — enforce key-based auth only
# /etc/ssh/sshd_config:
PasswordAuthentication no
PubkeyAuthentication yes
PermitRootLogin no

# 2. Deploy Fail2Ban for automated brute-force blocking
sudo apt install fail2ban -y
sudo systemctl enable fail2ban --now

# 3. Enforce MFA for all SSH sessions
sudo apt install libpam-google-authenticator -y

# 4. Move SSH from standard port 22 to reduce automated scanning
Port 2222

# 5. Restrict SSH access to management IPs only
AllowUsers admin@192.168.1.0/24
```

---

#### R-002 — Unpatched Services (vsftpd 2.3.4 Backdoor)

```
Risk Statement:   vsftpd 2.3.4 contains a known backdoor (CVE-2011-2523)
                  allowing remote code execution via malformed username

Category:         Vulnerability Management / Patch Management
Affected Assets:  FTP server (Port 21) — host 10.0.2.4
Threat Source:    External attackers — automated exploitation tools
Vulnerability:    CVE-2011-2523 — backdoor in vsftpd 2.3.4

Likelihood:   5 / 5  (exploit is public and automated)
Impact:       5 / 5  (full remote code execution)
Risk Score:   25 / 25  →  🔴 CRITICAL
Treatment:    MITIGATE / AVOID
```

**Treatment Actions for R-002:**

```bash
# Option 1: Remove FTP entirely (recommended)
sudo systemctl stop vsftpd
sudo apt remove vsftpd
# Replace with SFTP (SSH File Transfer Protocol) — already on port 22

# Option 2: If FTP required, upgrade to patched version
sudo apt update && sudo apt upgrade vsftpd

# Verify no backdoor version remains
vsftpd --version
```

---

#### R-003 — Telnet Running (Plaintext Protocol)

```
Risk Statement:   Telnet (Port 23) transmits all credentials and session
                  data in plaintext — susceptible to network interception

Category:         Network Security / Cryptographic Controls
Affected Assets:  Any host connecting via Telnet
Threat Source:    On-path attackers (AiTM), network sniffers
Vulnerability:    No encryption — credentials visible in packet capture

Likelihood:   4 / 5
Impact:       4 / 5
Risk Score:   16 / 25  →  🟠 HIGH
Treatment:    AVOID
```

**Treatment Actions for R-003:**

```bash
# Immediately disable Telnet
sudo systemctl stop telnet
sudo systemctl disable telnet
sudo apt remove telnetd

# Verify Telnet is no longer listening
ss -tlnp | grep :23
# Expected: No output

# Replace all Telnet usage with SSH
# Communicate to all users — Telnet access is terminated
```

---

#### R-004 — Samba 3.0.20 (CVE-Exploitable)

```
Risk Statement:   Samba 3.0.20-Debian contains multiple critical vulnerabilities
                  including authentication bypass and remote code execution

Category:         Network Security / Patch Management
Affected Assets:  File shares (Ports 139, 445) — WORKGROUP
Threat Source:    External and internal attackers
Vulnerability:    Multiple Samba 3.x CVEs — authentication bypass, RCE

Likelihood:   4 / 5
Impact:       5 / 5  (full file system access + RCE)
Risk Score:   20 / 25  →  🔴 CRITICAL
Treatment:    MITIGATE
```

---

## 📊 Risk Matrix

### 5×5 Risk Heat Map

```
                        IMPACT
              1-Min  2-Minor  3-Mod  4-Major  5-Severe
            ┌───────┬───────┬───────┬───────┬────────┐
5-Certain   │   5   │  10   │  15   │  20   │  25 🔴 │
4-Likely    │   4   │   8   │  12   │  16🟠 │  20 🔴 │
3-Possible  │   3   │   6   │   9   │  12🟠 │  15 🟠 │
2-Unlikely  │   2   │   4   │   6🟡 │   8🟡 │  10 🟡 │
1-Rare      │   1   │   2   │   3   │   4   │   5  🟢│
            └───────┴───────┴───────┴───────┴────────┘

🔴 Critical: 20–25  →  Immediate escalation + emergency remediation
🟠 High:     12–19  →  Urgent remediation — 7 days
🟡 Medium:    6–11  →  Planned remediation — 30 days
🟢 Low:        1–5  →  Monitor / Accept with documentation
```

### Current Risk Portfolio

| Risk ID | Description | Score | Level | Treatment |
|---------|-------------|-------|-------|-----------|
| R-002 | vsftpd 2.3.4 Backdoor (CVE-2011-2523) | **25** | 🔴 Critical | Mitigate/Avoid |
| R-004 | Samba 3.0.20 RCE/Auth Bypass | **20** | 🔴 Critical | Mitigate |
| R-005 | rexecd on Port 512 (unauth exec) | **20** | 🔴 Critical | Avoid |
| R-001 | Weak SSH Credentials | **16** | 🟠 High | Mitigate |
| R-003 | Telnet plaintext protocol | **16** | 🟠 High | Avoid |
| R-006 | Apache 2.2.8 / BIND 9.4.2 EOL | **12** | 🟠 High | Mitigate |
| R-007 | RPC portmapper enumeration | **8** | 🟡 Medium | Mitigate |
| R-008 | SMTP relay misconfiguration | **8** | 🟡 Medium | Mitigate |

---

## ✅ ISO 27001 Internal Audit Checklist

### Audit Overview

Internal audit conducted against **ISO 27001:2022** to identify compliance gaps.

**Audit Rating:**

| Symbol | Meaning |
|--------|---------|
| ✅ **Y** | Compliant — control fully implemented and evidenced |
| ⚠️ **P** | Partially Compliant — control exists but has gaps |
| ❌ **N** | Non-Compliant — control absent or significantly deficient |
| 🔵 **N/A** | Not Applicable to current scope |

---

### [1] Governance & Scope — Clause 4 & 6

| Ref | Audit Requirement | Evidence | Compliant | Comments |
|-----|------------------|----------|-----------|---------|
| **1.1** | Is the penetration testing program defined within the ISMS scope? | ISMS scope document | ✅ **Y** | Penetration testing formally included in ISMS scope; reviewed annually |
| **1.2** | Are vulnerability management activities included in ISMS boundaries? | ISMS scope, SoA | ✅ **Y** | Vulnerability management explicitly included in ISMS scope and SoA; roles and responsibilities defined |
| **1.3** | Are risks related to pentesting and vulnerability management identified in the risk assessment? | Risk assessment | ✅ **Y** | Risks assessed and documented with assigned risk owners; mitigation strategies defined |
| **1.4** | Are testing objectives mapped to identified security risks? | Risk assessment | ✅ **Y** | Testing objectives mapped to security risks |

📸 `screenshots/05_iso_audit_checklist.png`

---

### [2] Access Control — A.5.15 / A.8.2

| Ref | Audit Requirement | Compliant | Finding |
|-----|------------------|-----------|---------|
| **2.1** | Is MFA enforced for privileged accounts? | ⚠️ **P** | MFA policy exists; not enforced on all production SSH accounts |
| **2.2** | Are SSH keys used instead of passwords? | ❌ **N** | Password authentication still enabled — NMAP confirms SSH on Port 22 |
| **2.3** | Are access reviews conducted quarterly? | ⚠️ **P** | Annual reviews conducted; quarterly cadence not formalized |
| **2.4** | Is default/shared credential usage prohibited? | ❌ **N** | Evidence of shared credentials on production servers |

---

### [3] Vulnerability Management — A.8.8

| Ref | Audit Requirement | Compliant | Finding |
|-----|------------------|-----------|---------|
| **3.1** | Are systems scanned for vulnerabilities monthly? | ⚠️ **P** | Ad-hoc scanning practiced; no formal monthly schedule documented |
| **3.2** | Are critical vulnerabilities patched within 72 hours? | ❌ **N** | vsftpd 2.3.4 backdoor (2011) and Apache 2.2.8 (2008) remain unpatched |
| **3.3** | Is a vulnerability management policy in place? | ✅ **Y** | Policy developed as part of this capstone engagement |
| **3.4** | Are CVSS scores used to prioritize remediation? | ⚠️ **P** | CVSS scoring applied in this assessment; not yet integrated into ticketing workflow |

---

### [4] Network Security — A.8.20 / A.8.21

| Ref | Audit Requirement | Compliant | Finding |
|-----|------------------|-----------|---------|
| **4.1** | Are unnecessary services and ports disabled? | ❌ **N** | Telnet (23), rexecd (512), vsftpd (21) all open and unnecessary |
| **4.2** | Is network segmentation implemented? | ⚠️ **P** | Basic segmentation exists; production hosts not isolated from scan network |
| **4.3** | Are network services inventoried and approved? | ❌ **N** | No formal service inventory — NMAP revealed undocumented services |
| **4.4** | Is TLS enforced for all data in transit? | ❌ **N** | Telnet and FTP running — plaintext transmission confirmed |

---

### [5] Incident Management — A.5.24 / A.5.25

| Ref | Audit Requirement | Compliant | Finding |
|-----|------------------|-----------|---------|
| **5.1** | Is an incident response plan documented? | ⚠️ **P** | IRP exists at a high level; not tested in last 12 months |
| **5.2** | Are security incidents reported within defined SLAs? | ⚠️ **P** | Reporting process defined; escalation paths need formalization |

---

## 📜 Security Policies

Two formal organizational security policies were developed as deliverables of this engagement.

---

## 1. Penetration Testing Policy

### 1.0 Purpose

The purpose of this Penetration Testing Policy is to define the requirements, authorization, scope, and execution of penetration testing activities within the organization. The policy ensures testing is performed in a **controlled, safe, and compliant manner** to validate security controls, identify weaknesses, and support continuous improvement.

---

### 2.0 Scope

This policy applies to all organizational assets, including:

- Internal and external networks
- Servers, endpoints, and cloud infrastructure
- Web applications, APIs, and mobile applications
- Third-party hosted systems (where contractual permission exists)
- Employees, contractors, and third-party testers involved in testing activities

---

### 3.0 Policy Statement

The organization shall conduct penetration testing on a **recurring basis** and after significant changes to critical systems. All penetration testing must be:

```
✅ Approved by CISO / Security Manager
✅ Authorized in writing before commencement
✅ Documented with defined scope and methodology
✅ Executed in accordance with legal and regulatory requirements
```

---

### 4.0 Roles and Responsibilities

| Role | Responsibility |
|------|---------------|
| **CISO / Security Manager** | Approves testing, defines scope, ensures compliance |
| **IT Operations** | Provides system access, coordinates change windows, monitors stability |
| **Penetration Testers** | Conduct tests following OWASP, NIST, OSSTMM standards |
| **System Owners** | Ensure remediation plans completed per risk severity |

---

### 5.0 Rules of Engagement

```
REQUIRED:
├── Testing activities must be authorized in writing
├── Clear scope, timeframe, and methodology must be defined
├── Testers may not exceed agreed-upon boundaries ("no-touch zones")
├── Exploitation must avoid data corruption or service outages
├── Vulnerabilities must be reported immediately via secure channels
└── Sensitive data collected must be securely stored and destroyed after reporting
```

---

### 6.0 Frequency of Testing

```
Annual:         All critical systems
After changes:  Major system upgrades or architectural changes
Post-incident:  After significant security incident
On-demand:      When risk assessment identifies new material threats
```

---

### 7.0 Reporting Requirements

A final penetration test report must include:

- [ ] Executive summary
- [ ] Scope and methodology
- [ ] Identified vulnerabilities with CVSS severity ratings
- [ ] Proof-of-concept (where safe to include)
- [ ] Recommended remediation steps
- [ ] Metrics for tracking closure of findings

---

### 8.0 Compliance

> Violations of this policy may result in disciplinary action and could impact compliance with:
> **PCI-DSS · ISO 27001 · NIST 800-53 · HIPAA · GDPR**

---

## 2. Vulnerability Management Policy

### 1.0 Purpose

The purpose of the Vulnerability Management Policy is to ensure **timely identification, assessment, prioritization, and remediation** of security vulnerabilities across all organizational assets, thereby reducing exposure to threats and maintaining acceptable risk levels.

---

### 2.0 Scope

This policy applies to:

- All IT systems, applications, databases, network devices, and cloud resources
- All business units, employees, contractors, and third-party service providers
- All vulnerability sources including automation, manual testing, and threat intelligence feeds

---

### 3.0 Policy Statement

The organization shall maintain a **continuous vulnerability management program** that includes scanning, risk assessment, prioritization, remediation, verification, and reporting.

---

### 4.0 Roles and Responsibilities

| Role | Responsibility |
|------|---------------|
| **Security Team** | Vulnerability scanning, risk scoring, reporting |
| **IT Operations / System Owners** | Apply patches and implement remediation actions |
| **CISO / Security Manager** | Oversee vulnerability management lifecycle and compliance |
| **Third-Party Vendors** | Remediate vulnerabilities in managed systems per organizational SLAs |

---

### 5.0 Vulnerability Identification

```
Scanning Frequency:
├── All networks and systems          → At least MONTHLY
├── Critical infrastructure           → WEEKLY or continuous
├── Internet-facing assets            → MONTHLY external attack surface scan
└── Newly deployed systems            → BEFORE production release
```

---

### 6.0 Risk Rating & Remediation Timelines

All vulnerabilities classified using **CVSS v3.1** with internal risk modifiers:

```
┌─────────────────────────────────────────────────────────────────┐
│              REMEDIATION SLA SCHEDULE                           │
├──────────────────┬────────────────┬─────────────────────────────┤
│  Severity        │  CVSS Range    │  Maximum Remediation Time   │
├──────────────────┼────────────────┼─────────────────────────────┤
│  🔴 Critical     │  9.0 – 10.0    │  72 HOURS                   │
│  🟠 High         │  7.0 – 8.9     │  7 DAYS                     │
│  🟡 Medium       │  4.0 – 6.9     │  30 DAYS                    │
│  🟢 Low          │  0.0 – 3.9     │  90 DAYS                    │
└──────────────────┴────────────────┴─────────────────────────────┘

Exceptions require formal documented approval from CISO.
```

---

### 7.0 Patch & Remediation Process

```
REMEDIATION WORKFLOW:
1. Vulnerability identified by automated scan or manual testing
2. CVSS score assigned — severity classification applied
3. Risk ticket created in GRC/ticketing system
4. Remediation assigned to system owner with SLA deadline
5. Patch applied during approved maintenance window
6. Compensating controls implemented if patching delayed
7. Rescan performed to verify closure
8. Risk ticket closed with evidence documented
```

**Ansible Patch Automation (implemented as part of this engagement):**

```yaml
---
- name: Apply security patches — SecureEdge Ltd
  hosts: all
  become: yes
  tasks:
    - name: Update apt package cache
      apt:
        update_cache: yes

    - name: Apply all available security upgrades
      apt:
        upgrade: dist
        update_cache: yes

    - name: Enable automatic security updates
      copy:
        content: |
          APT::Periodic::Update-Package-Lists "1";
          APT::Periodic::Unattended-Upgrade "1";
        dest: /etc/apt/apt.conf.d/20auto-upgrades

    - name: Remove dangerous legacy services
      apt:
        name:
          - telnetd
          - vsftpd
          - rsh-server
        state: absent
```

---

### 8.0 Reporting & Metrics

```
Monthly Reporting Requirements:
├── Number of open vulnerabilities by severity
├── Mean Time to Remediate (MTTR) by severity tier
├── Percentage of systems compliant with patch timelines
├── Trends and recurring vulnerability patterns
└── Exception register — unpatched items with documented rationale
```

---

### 9.0 Compliance

> This policy supports compliance with:
> **ISO 27001 · CIS Controls v8 · NIST CSF · PCI-DSS · GDPR**
> Violations may result in disciplinary action.

---

## 🔑 Key Findings Summary

```
NMAP TECHNICAL FINDINGS — HOST 10.0.2.4:
├── 🔴 CRITICAL  Port 21   vsftpd 2.3.4 — known backdoor CVE-2011-2523
├── 🔴 CRITICAL  Port 23   Telnet — plaintext credentials exposed
├── 🔴 CRITICAL  Port 445  Samba 3.0.20 — RCE and auth bypass
├── 🔴 CRITICAL  Port 512  rexecd — unauthenticated remote execution
├── 🟠 HIGH      Port 22   OpenSSH 4.7p1 — outdated, brute-force risk
├── 🟠 HIGH      Port 53   BIND 9.4.2 — EOL, zone transfer vulnerability
├── 🟠 HIGH      Port 80   Apache 2.2.8 — EOL, multiple critical CVEs
├── 🟠 HIGH      Port 139  Samba 3.x — authentication bypass CVEs
├── 🟡 MEDIUM    Port 25   SMTP — relay misconfiguration risk
└── 🟡 MEDIUM    Port 111  RPC portmapper — service enumeration

ISO 27001 AUDIT FINDINGS:
├── ✅ COMPLIANT      Penetration testing included in ISMS scope (1.1)
├── ✅ COMPLIANT      Vulnerability management in ISMS boundaries (1.2)
├── ✅ COMPLIANT      Risks documented with owners and mitigations (1.3)
├── ❌ NON-COMPLIANT  MFA not enforced on all SSH accounts
├── ❌ NON-COMPLIANT  Legacy unpatched services running (vsftpd 2011, Apache 2008)
├── ❌ NON-COMPLIANT  No formal service inventory — undocumented services found
├── ❌ NON-COMPLIANT  Telnet and FTP in use — plaintext data transmission
└── ⚠️  PARTIAL       Monthly scanning not formally scheduled or documented

POLICIES DELIVERED:
├── ✅ Penetration Testing Policy — complete with RoE, frequency, reporting
└── ✅ Vulnerability Management Policy — CVSS-based SLAs, metrics, remediation workflow
```

---

## 📐 Frameworks & Compliance

| Framework | Application |
|-----------|-------------|
| **ISO 27001:2022** | Primary certification target — internal audit conducted clause by clause |
| **NIST CSF 2.0** | Identify, Protect, Detect functions mapped to all risk entries |
| **CIS Controls v8** | Linux hardening and patch management benchmarks |
| **CVSS v3.1** | Vulnerability severity scoring for all NMAP findings |
| **OWASP** | Web application security testing methodology |
| **NIST 800-53** | Control framework referenced in penetration testing policy |
| **MITRE ATT&CK** | Threat source mapping — T1110 (Brute Force SSH), T1190 (Exploit Public-Facing Application) |

---

## 🗂️ Repository Structure

```
grc-risk-assessment-secureedge/
│
├── README.md                              ← This file — full GRC documentation
│
├── policies/
│   ├── penetration_testing_policy.md      ← Formal penetration testing policy
│   └── vulnerability_management_policy.md ← Vulnerability management policy + SLAs
│
├── ansible/
│   └── patch_remediation.yml              ← Ansible playbook — patch and remove legacy services
│
├── screenshots/
│   ├── 01_cover_page.png                  ← Figure 1: Cover page
│   ├── 02_executive_summary.png           ← Figure 2: Executive summary
│   ├── 03_risk_register.png               ← Figure 3: Risk register (R-001)
│   ├── 04_nmap_scan.png                   ← Figure 4: NMAP scan results (10 ports)
│   └── 05_iso_audit_checklist.png         ← Figure 5: ISO 27001 audit checklist
│
└── reports/
    └── Justice_GRC_Capstone.pdf           ← Full GRC workbook export
```

---

## 🧰 Tools Used

| Tool | Purpose |
|------|---------|
| **Nmap** | Network port scanning and service fingerprinting |
| **Google Sheets** | GRC workbook — risk register, audit checklist, risk matrix |
| **Ansible** | Automated patch management and service remediation |
| **Fail2Ban** | SSH brute-force protection |
| **CVSS v3.1** | Vulnerability severity scoring |
| **ISO 27001:2022** | Compliance audit framework |
| **MITRE ATT&CK** | Threat source and TTP mapping |

---

## 👥 Team

| Name | Role |
|------|------|
| **Justice Alucho** | Risk Analyst / Cybersecurity Analyst |
| Philip Ufuah | Risk Analyst |
| Emmanuel Aderogba | Risk Analyst |
| Omotayo Ogunnika | Risk Analyst |
| Davidmarie Okon | Risk Analyst |

**Group:** Group 2 — NA
**Document Owner:** Group 2 — Chief Information Security Officers

---

## 👤 Author

<div align="center">

**Justice C. Alucho**
*Cybersecurity Analyst | GRC | ISO 27001 | Risk Assessment | SOC*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-justice--alucho-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/justice-alucho-30aba6145)
[![GitHub](https://img.shields.io/badge/GitHub-kosijustice-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kosijustice)
[![Email](https://img.shields.io/badge/Email-kosijustice7alucho@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kosijustice7alucho@gmail.com)

📍 Clemson, SC 29631

</div>

---

## 📄 License

This project is licensed under the MIT License — research and educational use.

---

<div align="center">

*⭐ If this GRC project demonstrates skills relevant to your team, feel free to star the repository.*

**ISO 27001 · NIST CSF · Risk Assessment · Nmap · GRC · Penetration Testing · Vulnerability Management**

`#GRC` `#ISO27001` `#RiskAssessment` `#VulnerabilityManagement` `#PenetrationTesting` `#Nmap` `#CyberSecurity` `#SOCAnalyst` `#Compliance` `#InformationSecurity`

</div>

