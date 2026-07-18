# PHIPA Compliance Checklist for Regulated SMBs

A practical, self-assessment checklist to help Ontario health information custodians — dental practices, clinics, physiotherapy and rehab providers, pharmacies, and their service providers — evaluate readiness against Ontario's **Personal Health Information Protection Act, 2004 (PHIPA)**.

> **Not legal advice.** This checklist is an operational readiness tool, not a legal opinion or a certification. It does not create a solicitor–client relationship and does not guarantee compliance. Confirm your specific obligations with legal counsel and the [Information and Privacy Commissioner of Ontario (IPC)](https://www.ipc.on.ca/). Where this checklist and the Act or IPC guidance differ, the Act and IPC guidance govern.

**How to use it:** Work through each domain and mark every item ✅ In place · 🟨 Partial · ❌ Missing · ➖ N/A. Anything not fully ✅ is a gap to prioritize. Re-run quarterly and after any material change to systems, staff, or vendors.

---

## Key PHIPA concepts (read first)

- **Health information custodian (HIC)** — the person or organization that has custody or control of personal health information (PHI) in the course of providing health care (e.g., a dental practice, clinic, or pharmacy).
- **Agent** — a person or organization that acts for or on behalf of a custodian with respect to PHI (e.g., staff, contractors, some IT providers). Agents may only handle PHI as permitted by the custodian.
- **Personal health information (PHI)** — identifying information about an individual relating to their physical or mental health, health care, payments or eligibility for care, and related identifiers such as the health card number.
- **Circle of care** — the informal term for the group of custodians permitted to rely on assumed implied consent to collect, use, and disclose PHI for the provision of health care.

---

## 1. Governance & Accountability

- [ ] A **contact person** (privacy officer or equivalent) is formally designated to oversee PHIPA compliance and respond to inquiries and complaints.
- [ ] A written **privacy program / information practices** document describes how PHI is collected, used, disclosed, retained, and disposed of.
- [ ] Roles and responsibilities for privacy and security are documented and assigned.
- [ ] A current **inventory of PHI** exists — what is held, where it lives (systems, paper, backups, cloud), and who has access.
- [ ] A **data flow map** shows how PHI moves into, through, and out of the practice, including third parties.
- [ ] Compliance is reviewed on a defined schedule (at least annually) and after material changes.
- [ ] The organization can demonstrate **accountability** — policies exist *and* there is evidence they are followed.

## 2. Consent & Patient Rights

- [ ] Reliance on **implied consent** within the circle of care is understood and applied correctly.
- [ ] Processes exist to obtain **express consent** where required (e.g., disclosures outside the circle of care, marketing, fundraising).
- [ ] Patients can **withhold or withdraw consent** ("lockbox"), and staff know how to apply and honour a consent directive.
- [ ] A process exists for patients to **access their own records** within the timelines PHIPA requires.
- [ ] A process exists for patients to **request correction** of their records, and to attach a statement of disagreement where a correction is refused.
- [ ] A **public-facing privacy notice** describes information practices and how to contact the custodian and the IPC.

## 3. Administrative Safeguards

- [ ] **Confidentiality agreements** are signed by all staff, contractors, and students with access to PHI.
- [ ] **Privacy and security awareness training** is delivered at onboarding and refreshed at least annually.
- [ ] **Access is role-based** and follows least privilege — people can reach only the PHI they need.
- [ ] A **joiner/mover/leaver** process promptly grants, changes, and revokes access as roles change.
- [ ] **Written agreements** are in place with every service provider that touches PHI (see Domain 7).
- [ ] **Sanctions** for privacy breaches by agents are defined and communicated.
- [ ] Policies cover acceptable use, remote/mobile work, email, and social media as they relate to PHI.

## 4. Technical Safeguards

- [ ] **Unique user accounts** for every individual — no shared logins.
- [ ] **Strong authentication**, including **multi-factor authentication (MFA)** for remote access, email, and administrative accounts.
- [ ] **Encryption in transit** (TLS) for all PHI moving over networks, including email and portals.
- [ ] **Encryption at rest** for servers, workstations, laptops, mobile devices, and backups.
- [ ] **Endpoint protection** (anti-malware / EDR) deployed and monitored on all devices handling PHI.
- [ ] **Patch and vulnerability management** keeps operating systems, applications, and firmware current.
- [ ] **Firewall and network segmentation** separate clinical systems from guest and general-use networks.
- [ ] **Audit logging** records access to PHI, and logs are retained and reviewed for anomalies.
- [ ] **Secure disposal** of electronic media (secure wipe or destruction) before disposal or reuse.
- [ ] **Backups** are encrypted, access-controlled, and **tested by periodic restore**.

## 5. Physical Safeguards

- [ ] Servers and network equipment are in a **locked, access-controlled** location.
- [ ] Workstations are positioned and locked so screens are not visible to unauthorized people.
- [ ] **Paper records** are stored in locked cabinets or rooms with controlled access.
- [ ] Visitor access to areas containing PHI is controlled and, where appropriate, logged.
- [ ] **Secure destruction** of paper PHI (cross-cut shredding or a certified service) is in place.
- [ ] Devices are physically secured against theft (cable locks, secured rooms, asset tracking).

## 6. Breach Management

- [ ] A written **privacy breach response plan** defines detection, containment, assessment, notification, and remediation.
- [ ] Staff know **how to report** a suspected breach and to whom, without fear of reprisal for good-faith reporting.
- [ ] The organization can **notify affected individuals** at the first reasonable opportunity when required.
- [ ] The organization understands when it must **notify the IPC** and, where applicable, a **regulatory college**.
- [ ] Breaches and near-misses are **logged**, and root-cause analysis feeds back into controls.
- [ ] The organization tracks its **annual statistics** on breaches for the IPC reporting obligation.
- [ ] The breach plan is **tested** (tabletop exercise) at least annually.

## 7. Third-Party & Vendor Risk

- [ ] Every vendor handling PHI is identified, and its role (agent vs. independent custodian) is understood.
- [ ] **Written agreements** address permitted use, safeguards, breach notification timelines, return/destruction of PHI, and audit rights.
- [ ] **Data residency** is known and acceptable — where PHI is stored and processed, including any storage or access outside Canada.
- [ ] Cloud and software providers' **security posture** is assessed (e.g., SOC 2, ISO 27001, or equivalent evidence).
- [ ] Sub-processors used by your vendors are disclosed and acceptable.
- [ ] Vendor access is **least-privilege**, monitored, and revoked promptly when the relationship ends.

## 8. Retention, Records & Continuous Improvement

- [ ] A **records retention and destruction schedule** reflects legal, regulatory, and professional-college requirements.
- [ ] PHI is **securely destroyed** at end of life following the schedule.
- [ ] Policies and this assessment are **reviewed on a schedule** and version-controlled.
- [ ] Findings from breaches, audits, and complaints drive documented **corrective actions**.
- [ ] Evidence (training records, logs, agreements, test results) is **retained** to demonstrate compliance.

---

## Scoring your readiness

| Result | What it means | Action |
|---|---|---|
| Mostly ✅ | Strong posture | Maintain; re-assess quarterly |
| Several 🟨 | Partial controls | Close partials before they become findings |
| Any ❌ in Domains 4, 6, or 7 | High-risk gap | Prioritize immediately |

A single ❌ in breach management, technical safeguards, or vendor risk carries more exposure than several partials elsewhere — those are where incidents and IPC scrutiny concentrate.

---

## References

- [Personal Health Information Protection Act, 2004 (PHIPA) — Ontario](https://www.ontario.ca/laws/statute/04p03)
- [Information and Privacy Commissioner of Ontario (IPC)](https://www.ipc.on.ca/)
- [IPC — Health Privacy resources](https://www.ipc.on.ca/en/health-organizations)

---

*Maintained by [Security Assured](https://securityassured.ca). Contributions and corrections welcome via pull request or issue.*
