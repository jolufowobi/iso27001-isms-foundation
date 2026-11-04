ISO/IEC 27001:2022 ISMS Foundation | Health-Tech Organization
1. Summary
This project builds the governance foundation of an Information Security Management System (ISMS) aligned to ISO/IEC 27001:2022 for a health-tech organization. The organization provides AI diagnostics and remote patient monitoring to 300+ healthcare facilities across two cloud platforms, and had no unified policy framework, informal access management and no incident response process.
The work covers the full governance layer an ISMS needs before controls can be implemented and audited: scope and governance, risk, regulatory mapping, a policy suite, operating procedures, document control and board reporting.
Deliverable	Count
Governance artefacts	20
Policies (1 master + 9 topic policies)	10
Control statements	167
Standard Operating Procedures (SOPs)	5
Rated risks in the project risk register	11
Quality review findings closed	13
2. Risk and Regulatory Context
Risk area	Why it mattered
Ransomware and service disruption	An outage would stop diagnostics and monitoring that hospitals rely on
Regulatory exposure	GDPR, HIPAA (for US expansion) and EU Medical Device Regulation obligations for AI diagnostic tools
Weak cloud and supplier governance	Two clouds, hospital API integrations and multiple security vendors with no consistent requirements
Failed customer security audits	No policies or evidence to answer customer security questionnaires
I also reviewed two public healthcare incidents (a ransomware attack on a pathology supplier and a large prescription data breach) to identify the governance failures behind them and use those lessons in the ISMS priorities.
3. Governance and Scope
ISMS project charter: scope, objectives and success criteria, governance structure, communication plan, timeline and milestones.
RACI: responsibilities across the Board, Steering Committee, Information Security Manager, Data Protection Officer, IT and business owners.
Project risk register: 11 risks rated for likelihood and impact, each with an owner and treatment action, including supplier and cloud risks.
Roadmap: a phased plan towards ISO 27001 and SOC 2 readiness.
4. Regulatory Mapping
Built an ISMS concept map linking governance, policies, risk management, controls and continuous improvement.
Mapped GDPR, HIPAA and medical device obligations across seven business operations (including AI diagnostics, remote monitoring and EMR integrations) into one integrated control set.
Covered data processor obligations, international transfers, breach notification timelines and Data Protection Impact Assessment (DPIA) requirements.
5. Policy Suite
A standardized policy template (document control, owner, approver, contacts, classification, review dates) was used for every document.
Level	Document
Level 1	Master Information Security Policy
Level 2	Acceptable Use Policy
Level 2	Human Resources Security Policy
Level 2	Business Continuity and Disaster Recovery Policy
Level 2	Data Protection and Privacy Policy
Level 2	Access Control Policy
Level 2	Incident Response Policy
Level 2	Asset Management Policy
Level 2	Vulnerability Management Policy
Level 2	Physical Security Policy
Each of the 167 control statements has an owner, an evidence requirement and an ISO/IEC 27001:2022 Annex A reference. Statements are written to be measurable, for example patching timelines by severity and quarterly access reviews.
Third-party management is covered at Level 1: suppliers are security-assessed before onboarding, critical suppliers are reviewed every year, and contracts cover security, breach notification, data processing, subcontractors, assurance evidence and exit arrangements (Annex A 5.19–5.23).
Business resilience is covered through BC/DR and incident response requirements: business impact analysis, recovery tiers with RTO, RPO and MTPD targets, and twice-yearly incident response exercises.
6. Standard Operating Procedures
SOP	Parent policy
User Access Management	Access Control
Human Resources Security	HR Security
Physical and Environmental Security	Physical Security
Incident Management	Incident Response
Business Continuity and Disaster Recovery	BC/DR
7. Document Control and Quality Review
Master Policy Register and SOP Register: document number, title, owner, version, status, last reviewed, next review date, hierarchy level, approver and classification.
Completeness check: every document checked against the required metadata fields.
Quality review: 13 findings identified and closed, such as adding a missing contacts field to every policy and confirming that the master policy's list of topic policies matched the approved suite.
8. Board Reporting
Prepared a board report and presentation that set out what was built, why it mattered and what the Board needed to decide. The report asked for five decisions:
Endorse the ISMS scope, policies and SOPs as the organization's security framework.
Approve a risk appetite statement, with low appetite for risks to patient safety and patient data.
Fund the implementation phase.
Commit to certification dates.
Receive quarterly ISMS reports.
9. Practitioner Notes
I gave every control statement an owner and an evidence requirement so each one can be tested later, and ran the quality review before anything reached approval. The board report focused on decisions, owners and dates, because a framework only starts working once someone is accountable for each part of it.
10. Scope
The documents in this repository have been anonymized. Approval statuses reflect the documented governance process; implementation, control testing and certification are later phases.
11. Frameworks and Standards
ISO/IEC 27001:2022 and Annex A
ISO/IEC 27002
SOC 2
GDPR
HIPAA
EU Medical Device Regulation (MDR)
---
Project: ISO/IEC 27001:2022 ISMS Foundation | Health-Tech Organization
Role: Cybersecurity GRC Consultant
Domain: Information Security Governance | GRC | Privacy
