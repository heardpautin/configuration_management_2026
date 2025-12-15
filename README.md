# 🔐 Configuration Management & Baseline Enforcement
## Security-Focused Configuration Governance (IAM • GRC • Cloud • Healthcare • Federal)

---

## 📘 Overview

This project demonstrates **Configuration Management as a security, governance, and risk control**, not traditional system administration.

The focus is on how disciplined configuration practices:

- Preserve **approved security baselines**
- Prevent and detect **configuration drift**
- Enforce **least privilege**
- Support **audit readiness** and regulatory compliance

This project reflects real-world expectations in **regulated environments**, including healthcare, federal/DoD programs, and financial institutions.

> **Important Note**  
> All examples in this repository are **lab-based or simulated**.  
> No proprietary, production, or employer-specific data is included.

---

## 🛡️ Why Configuration Management Is a Security Function

Configuration decisions directly impact:

- Identity permissions and access paths
- System hardening and exposure
- Audit outcomes
- Regulatory compliance

Weak configuration control leads to:

- Privilege creep
- Unauthorized access
- Failed audits
- Increased security risk

This project treats configuration items as **governed security artifacts**, subject to approval, monitoring, and evidence collection.

---

## 📋 Framework & Control Alignment

This project aligns configuration management activities with widely adopted security and compliance frameworks.

### NIST SP 800-53 (Rev. 5)
- **CM-2** – Baseline Configuration
- **CM-3** – Configuration Change Control
- **CM-5** – Access Restrictions for Change
- **CM-6** – Configuration Settings
- **CM-7** – Least Functionality
- **IA-2 / IA-5** – Identification & Authentication
- **AC-2 / AC-6** – Account Management & Least Privilege

### NIST Cybersecurity Framework (CSF)
- **ID.GV** – Governance
- **PR.IP** – Information Protection Processes
- **DE.CM** – Continuous Monitoring

### ISO/IEC 27001
- **A.8** – Asset Management
- **A.9** – Access Control
- **A.12** – Operations Security
- **A.14** – System Acquisition, Development & Maintenance

### DoD / STIG Philosophy
- Approved baselines
- Configuration drift detection
- Continuous compliance

---

## 🎯 Project Scope

This repository focuses on **security-centric configuration management**, including:

- Configuration baseline definition
- Change control and documentation
- Configuration drift detection
- Remediation and baseline restoration
- Identity-centric configuration management
- Audit evidence preparation

The scope intentionally avoids system-specific administration in favor of **repeatable governance patterns**.

---

## ⚙️ Section 1: Configuration Baseline Definition

**Objective:**  
Define what a *secure, approved configuration* looks like before changes occur.

### Baseline Examples
- Identity group membership
- Role and privilege assignments
- Conditional Access policies
- Security hardening settings
- Approved access patterns

### Example Artifacts
- RBAC matrices
- Group-to-role mappings
- Baseline policy documentation

📸 **Evidence Placeholder:**  
Approved baseline documentation (RBAC matrix, role definitions, policy exports)

**What This Demonstrates**
- Security starts with **defined baselines**
- Policy translated into **technical standards**
- Configuration treated as a **governed artifact**

---

## 📝 Section 2: Change Control & Documentation

**Objective:**  
Ensure all configuration changes are authorized, documented, and traceable.

### Change Control Elements
- Change request identification
- Business justification
- Risk assessment
- Approval record
- Implementation evidence

### Example Change Record Fields
- Change ID
- Configuration Item (CI)
- Before state
- After state
- Approver
- Implementation date

📸 **Evidence Placeholder:**  
Change logs and before/after configuration comparisons

**What This Demonstrates**
- Strong audit trails
- Defensible configuration decisions
- Prevention of unauthorized change

---

## 🔍 Section 3: Configuration Drift Detection

**Objective:**  
Identify deviations from approved baselines.

### Drift Examples
- Unauthorized group memberships
- Excess permissions
- Modified security settings
- Out-of-policy configurations

### Detection Methods
- Manual reviews
- Periodic access reviews
- Configuration comparisons
- Script-based checks

📸 **Evidence Placeholder:**  
Drift detection output and comparison results

**What This Demonstrates**
- Continuous monitoring mindset
- Drift treated as a **security risk**
- Alignment with compliance requirements

---

## ♻️ Section 4: Remediation & Baseline Restoration

**Objective:**  
Return systems to an approved, secure state after drift is detected.

### Remediation Actions
- Remove unauthorized access
- Restore approved configuration
- Document corrective actions
- Validate post-remediation state

📸 **Evidence Placeholder:**  
Post-remediation validation artifacts

**What This Demonstrates**
- Closed-loop security operations
- Corrective action discipline
- Support for audit closure

---

## 🧩 Section 5: Identity-Centric Configuration Management

**Objective:**  
Demonstrate how **IAM is fundamentally a configuration management problem**.

### Identity Configurations Managed
- Group membership
- Role assignments
- Privileged access
- Distribution lists
- Joiner / Mover / Leaver lifecycle changes

### Examples
- Removing legacy access during role changes
- Enforcing least privilege
- Preventing segregation-of-duties conflicts

📸 **Evidence Placeholder:**  
Identity configuration changes (before/after)

**What This Demonstrates**
- IAM beyond provisioning
- Governance-driven access control
- Reduction of insider risk and privilege creep

---

## 🏥 Section 6: Healthcare & Enterprise Context

Healthcare and regulated enterprises require:

- Strict access controls
- Auditable change histories
- Minimal operational disruption
- Regulatory defensibility (HIPAA, HITECH)

Configuration management ensures:

- Continuous compliance
- Controlled administrative activity
- Defensible access decisions

This directly supports IAM oversight, configuration management, and GRC roles.

---

## 🗂️ Section 7: Evidence & Audit Readiness

### Evidence Collected
- Baseline documentation
- Change approvals
- Drift detection output
- Remediation validation
- Access review artifacts

### Audit Use Cases
- Internal audits
- External audits
- Compliance reviews
- Management reporting

📸 **Evidence Placeholder:**  
Organized audit evidence structure

**What This Demonstrates**
- Auditor-ready thinking
- Proactive evidence collection
- Reduced audit friction

---

## ✅ Summary

This project demonstrates that:

- Configuration Management is a **core security control**
- Identity, cloud, and governance are interconnected
- Secure systems depend on **maintained baselines**
- Audit readiness is built continuously, not retroactively

This is not system administration.

This is **security governance through configuration discipline**.

---

## 🚀 Future Enhancements

- Automated drift detection
- CI/CD policy enforcement
- Infrastructure-as-Code baseline validation
- Continuous compliance reporting

---

## 👤 Author

**Craig W. Heard**  
IAM • GRC • Cloud Security  
San Antonio, TX  

- GitHub: https://github.com/heardpautin  
- LinkedIn: https://linkedin.com/in/craig-heard
