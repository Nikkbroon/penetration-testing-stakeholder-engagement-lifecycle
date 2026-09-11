# Penetration Testing Stakeholder Engagement Life Cycle

## Overview

This project presents a stakeholder engagement and governance lifecycle that I developed for professional penetration testing engagements.

The framework demonstrates that a successful penetration test involves considerably more than technical vulnerability discovery and exploitation. Effective penetration testing also requires clear communication, legal authorisation, defined Rules of Engagement, risk management, stakeholder involvement, structured reporting, remediation and formal project closure.

The lifecycle is aligned with the EC-Council penetration testing methodology studied during my cyber security degree while incorporating my own approach to stakeholder engagement, governance and project management.

The framework follows a penetration testing engagement from initial customer contact through planning, authorisation and technical testing to reporting, remediation, retesting and final project closure.

---

## Project Aim

The aim of this project was to design a practical lifecycle showing how technical penetration testing activities can be integrated with stakeholder engagement and governance.

The framework was designed to:

- establish clear customer expectations before testing begins
- define testing goals, scope, targets, timings and responsibilities
- ensure appropriate legal authorisation is obtained
- establish formal Rules of Engagement
- maintain communication throughout the penetration test
- provide escalation routes for critical security findings
- control higher-risk testing activities
- communicate technical findings to technical and non-technical stakeholders
- support remediation and vulnerability retesting
- provide a defined process for formal project closure

---

## Stakeholder Engagement Life Cycle

The lifecycle consists of the following stages:

1. Establish Customer Contact
2. Build and Maintain Stakeholder Engagement
3. Design Customer Proposal(s)
4. Present Customer Proposal(s)
5. Obtain Legal Permissions
6. Establish Rules of Engagement
7. Agree and Sign Non-Disclosure Agreement (NDA)
8. Begin Penetration Test
9. Reconnaissance and Threat Modelling
10. Scanning, Enumeration and Vulnerability Analysis
11. Gaining Access / Exploitation
12. Maintaining Access – Optional
13. Clearing Tracks – Optional
14. Analysis and Post-Exploitation
15. Reporting
16. Remediation
17. Retesting
18. Project Closure

---

## Framework Diagram


<img width="690" height="666" alt="Screenshot 2026-09-11 at 15 49 17" src="https://github.com/user-attachments/assets/96102b28-66b4-410d-8834-f82a152fe1bd" />

<img width="674" height="310" alt="Screenshot 2026-09-11 at 15 49 35" src="https://github.com/user-attachments/assets/1200f703-166b-4f9e-a323-37a224cb0a63" />

<img width="675" height="287" alt="Screenshot 2026-09-11 at 15 49 40" src="https://github.com/user-attachments/assets/795e9071-2957-4f15-ba3c-e792cb86330f" />



## Penetration Test Planning

Planning establishes the boundaries and expectations of the penetration testing engagement before technical testing begins.

The planning stage considers:

- goals and objectives
- authorised IP ranges and domains
- White Box or Black Box testing
- testing timings
- costs and payment terms
- authorised personnel
- network, application and cloud testing
- social engineering and physical security testing

The expected output from this stage is a clearly defined Statement of Work and supporting scope documentation.

---

## Rules of Engagement and Governance

Rules of Engagement provide continuous governance throughout the penetration testing lifecycle.

The framework treats the Rules of Engagement as an ongoing control rather than simply a document agreed at the beginning of the engagement.

Testing activities must remain within the agreed scope and authorisation throughout the project.

Changes to scope, unexpected risks or potentially disruptive testing activities should be communicated to the appropriate stakeholders before proceeding.

This provides clear boundaries around what the penetration tester is authorised to do and helps protect both the customer and the tester.

---

## Legal Permissions and Confidentiality

Formal legal permission must be obtained before penetration testing begins.

The lifecycle includes:

- formal customer authorisation
- agreed Rules of Engagement
- Non-Disclosure Agreements
- defined communication channels
- escalation procedures
- authorised testing boundaries

These controls ensure that penetration testing activities are conducted with documented customer approval and that sensitive information obtained during the engagement is appropriately protected.

---

## Continuous Stakeholder Communication

A continuous stakeholder feedback loop operates throughout the engagement.

Defined communication channels include:

- primary technical contacts
- emergency escalation leads
- executive sponsors
- daily status reports
- critical vulnerability alerts

This allows technical findings, operational risks and changes to scope to be communicated while the penetration test is taking place rather than waiting until the final report.

Real-time risk and scope feedback also provides a mechanism for responding to unexpected findings or operational concerns during testing.

---

## Reconnaissance and Threat Modelling

The technical testing process begins with reconnaissance and threat modelling.

This stage involves passive and active information gathering to identify potential attack vectors and understand the target environment.

The objective is to develop an understanding of the organisation's attack surface while remaining within the agreed Rules of Engagement.

A potential deliverable from this stage is an OSINT profile documenting relevant information identified during reconnaissance.

---

## Scanning, Enumeration and Vulnerability Analysis

Scanning and enumeration are used to identify systems, services, network exposure and potential weaknesses.

Vulnerability analysis combines automated and manual techniques to identify vulnerabilities and security misconfigurations within authorised assets.

The output from this phase contributes towards the vulnerability list that will guide subsequent testing.

---

## Gaining Access and Exploitation

Confirmed vulnerabilities may be subjected to controlled exploitation where this is permitted by the Rules of Engagement.

Exploitation is performed to demonstrate whether an identified vulnerability could result in genuine compromise.

Critical findings may require immediate communication rather than waiting for the final penetration testing report.

The lifecycle therefore includes Flash Vulnerability Alerts to ensure significant risks can be escalated quickly to the customer.

---

## Higher-Risk Testing Activities

The lifecycle identifies Maintaining Access and Clearing Tracks as optional phases because these activities introduce additional operational and security risks.

### Maintaining Access

Maintaining Access may involve assessing persistence mechanisms or privilege retention to determine whether an attacker could retain access to a compromised system.

These activities require explicit pre-authorisation within the Rules of Engagement.

A potential deliverable is a Persistence Assessment Log.

### Clearing Tracks

Clearing Tracks may involve evaluating defensive detection capabilities by testing activities such as log modification or artefact removal.

These activities also require explicit pre-authorisation.

A potential deliverable is an Evasion and Audit Log Report.

These optional phases must only be performed where they have been specifically authorised by the customer and documented within the Rules of Engagement.

---

## Analysis and Post-Exploitation

Post-exploitation analysis examines the wider implications of a successful compromise.

This includes considering:

- extent of compromise
- potential business impact
- access to sensitive information
- privilege levels obtained
- possible attack paths
- escalation opportunities

The purpose is not simply to demonstrate that a vulnerability exists but to understand what that vulnerability could mean to the organisation.

An Impact Matrix can be used to communicate these findings.

---

## Reporting

Reporting converts technical findings into information that stakeholders can understand and act upon.

The lifecycle includes both technical and executive-level reporting.

Potential report content includes:

- Executive Summary
- Technical Findings Matrix
- vulnerability descriptions
- risk ratings
- supporting evidence
- remediation guidance
- strategic mitigation recommendations

Both draft and final penetration testing reports can be produced as part of the engagement.

---

## Post-Test Deliverables

The framework identifies a number of potential deliverables throughout the penetration testing engagement:

- Proposal and Scoping Document
- Statement of Work
- signed Rules of Engagement
- signed Non-Disclosure Agreement
- OSINT Profile
- Vulnerability List
- Flash Vulnerability Alerts
- Persistence Assessment Log
- Evasion and Audit Log Report
- Impact Matrix
- Draft Penetration Test Report
- Final Penetration Test Report
- Remediation Roadmap
- Retest Verification Report
- Project Closure Certificate

This ensures that the penetration test produces documented evidence and actionable information throughout the engagement rather than relying solely on a final technical report.

---

## Remediation

The penetration test does not end when vulnerabilities have been identified.

The remediation stage provides an opportunity to support customer engineering and security teams in understanding identified weaknesses and determining appropriate corrective actions.

A Remediation Roadmap can be used to prioritise vulnerabilities and guide security improvements.

---

## Retesting

Retesting verifies whether previously identified vulnerabilities have been successfully addressed.

Previously affected assets can be reassessed to confirm that security fixes have been correctly implemented and that the original vulnerability can no longer be exploited.

The outcome can be documented within a Retest Verification Report.

This creates a clear progression from:

Discovery → Evidence → Reporting → Remediation → Verification

---

## Project Closure

Formal project closure provides a controlled end to the penetration testing engagement.

Closure activities may include:

- confirming completion of agreed testing
- issuing final reports
- confirming remediation and retesting results
- returning or securely destroying sensitive customer information
- documenting lessons learned
- obtaining final stakeholder sign-off

A Project Closure Certificate can provide formal confirmation that the engagement has concluded.

---

## Skills Demonstrated

This project demonstrates my understanding of:

- penetration testing lifecycle design
- stakeholder engagement
- penetration testing governance
- Rules of Engagement
- penetration testing scoping
- legal and ethical authorisation
- Non-Disclosure Agreements
- risk management
- vulnerability escalation
- technical security testing
- technical and executive reporting
- remediation planning
- vulnerability retesting
- project closure
- professional security communication
- EC-Council penetration testing methodology

---

## Project Reflection

Developing this lifecycle helped strengthen my understanding of the importance of stakeholder engagement within professional penetration testing.

Technical ability is essential, but a penetration tester must also understand exactly what they are authorised to test, where the boundaries of an engagement exist, how findings should be communicated and when a testing activity could introduce unacceptable operational or business risk.

I designed the framework to connect technical penetration testing activities with the legal, governance and communication processes that support them.

One of the most important aspects of the framework is the continuous stakeholder feedback loop. Rather than treating stakeholder communication as something that occurs only at the beginning and end of an engagement, the lifecycle integrates communication throughout the penetration test.

The inclusion of optional higher-risk phases also demonstrates the importance of explicit authorisation. Activities involving persistence or clearing tracks should never be assumed to be permitted simply because general penetration testing authorisation has been provided.

Overall, this project strengthened my understanding of how penetration testing can be conducted in a controlled, accountable and professionally governed manner.
