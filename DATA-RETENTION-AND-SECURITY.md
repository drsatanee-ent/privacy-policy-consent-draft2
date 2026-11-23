# Data Retention and Security Framework (Sample)

## 1. Purpose
This framework describes sample controls for a fictional online service. Actual retention periods and security measures must be based on the service's purposes, risks, contractual commitments, and legal obligations.

## 2. Sample Retention Schedule
The periods below are illustrative placeholders, not legal defaults.

| Data category | Purpose | Proposed retention | End-of-period action |
|---|---|---|---|
| Account profile | Provide account service | While account is active; review after closure | Delete or de-identify unless retention is justified |
| Support correspondence | Resolve inquiries and disputes | [e.g., 24 months after closure] | Delete or restrict access |
| Security logs | Detect and investigate incidents | [e.g., 12 months] | Secure deletion / aggregation |
| Consent records | Demonstrate consent and honor preferences | While relied upon and for a justified evidence period | Minimize and securely retain or delete |
| Billing records | Accounting and legal compliance | As required by applicable law | Securely delete when no longer required |

Document the rationale, owner, exceptions, and deletion method for every category. Review the schedule periodically.

## 3. Security Control Baseline
### Governance
- Assign data owners and system administrators.
- Maintain an inventory of personal-data processing activities.
- Perform privacy and security risk assessments for new or changed processing.
- Train staff on confidentiality and incident reporting.

### Technical
- Enforce least-privilege access and multi-factor authentication where appropriate.
- Encrypt data in transit and protect stored data according to risk.
- Store passwords using a modern, salted password-hashing algorithm; never store plaintext passwords.
- Patch dependencies and systems; scan for vulnerabilities.
- Maintain secure backups and test restoration.
- Log privileged access and security-relevant events; protect logs from tampering.

### Organizational
- Use confidentiality commitments and role-based training.
- Review processor security and contractual safeguards.
- Establish secure data disposal procedures.
- Test incident-response procedures.

## 4. Personal Data Breach Response
1. Detect and report suspected incidents promptly through [internal channel].
2. Contain the incident and preserve relevant evidence.
3. Assess the type and volume of data, affected individuals, likely consequences, and mitigation options.
4. Escalate to the privacy lead, security lead, and legal counsel.
5. Determine whether notification to the regulator and affected individuals is required under the PDPA and current notifications/guidance. Observe applicable statutory timelines and document the decision.
6. Remediate root causes and record lessons learned.

Do not assume every incident requires the same notification. Make a documented, fact-specific assessment.

## 5. Processor Management
- Maintain a list of processors and sub-processors.
- Define processing instructions, confidentiality, security, breach support, deletion/return, and audit obligations in contracts.
- Review access and service scope periodically.
- Verify deletion or return at contract termination.

## 6. Review Cycle
Review this framework at least annually and whenever there is a material change to the service, data categories, vendors, threat environment, or applicable law.
