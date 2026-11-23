# Privacy Policy & Consent Documentation
**Portfolio Demonstration | Thailand Personal Data Protection Act (PDPA)**

## Project Overview
This repository contains a sample set of privacy documents for a fictional general-purpose digital service. It demonstrates how privacy requirements can be translated into user-facing notices, consent language, operational controls, and implementation checklists.

> **Important:** Educational portfolio template only — not legal advice or a production-ready policy. Replace placeholders, map actual data flows, identify the correct lawful basis for each purpose, and obtain qualified legal/privacy review before use.

## Scope and Assumptions
The fictional service allows users to create accounts, manage profiles, and contact customer support. It does not assume processing of health data, biometric data, children's data, or other sensitive personal data. If such data is processed, conduct a separate assessment and implement additional safeguards.

## Repository Contents
| File | Purpose |
|---|---|
| [PRIVACY-POLICY.md](PRIVACY-POLICY.md) | Sample privacy policy |
| [PRIVACY-NOTICE.md](PRIVACY-NOTICE.md) | Notice at the point of collection |
| [CONSENT-FORM.md](CONSENT-FORM.md) | Optional consent and withdrawal wording |
| [DATA-SUBJECT-RIGHTS.md](DATA-SUBJECT-RIGHTS.md) | Rights request workflow |
| [DATA-RETENTION-AND-SECURITY.md](DATA-RETENTION-AND-SECURITY.md) | Retention and security controls |
| [IMPLEMENTATION-CHECKLIST.md](IMPLEMENTATION-CHECKLIST.md) | Practical readiness checklist |

## How to Adapt
1. Map every personal-data field, source, recipient, and system.
2. Determine and document the lawful basis for each processing activity.
3. Collect consent only where it is the appropriate lawful basis; keep optional consent separate from core service terms.
4. Set retention periods based on actual operational and legal requirements.
5. Establish rights-request, access-control, deletion, and incident-response procedures.
6. Review the documents with qualified counsel and the responsible privacy function.

## Demonstrated Skills
Privacy-by-design thinking, requirements documentation, data lifecycle analysis, consent UX, risk identification, and technical/operational control mapping.

## References
- Thailand Personal Data Protection Act B.E. 2562 (2019) — consult the official published text and current regulator guidance.
- Personal Data Protection Committee (PDPC), Thailand — consult current announcements, notifications, and guidance.

**Version:** 1.0 | **Status:** Sample / for demonstration only


## Working Prototype

An interactive front-end demonstration is available in the repository root:
- `index.html` — application structure and screens
- `styles.css` — responsive interface
- `app.js` — consent controls, local persistence, activity log, and JSON export

### Run locally
Open `index.html` in a modern browser. No build step or dependencies are required.

### Deploy with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then Save.
4. Wait for the deployment and open the Pages URL shown in Settings → Pages.

### Demo capabilities
- Separate optional consent choices for analytics and marketing.
- Save and review the latest preference state.
- Withdraw optional consent.
- View an activity log and export demo records as JSON.
- Data is stored only in the current browser's Local Storage.

> **Important:** This is a front-end educational prototype only. It has no authentication, server-side audit log, database, encryption-at-rest controls, or production security controls. Do not enter real personal, health, or sensitive data. The sample notice and legal wording must be reviewed and adapted before any real deployment.
