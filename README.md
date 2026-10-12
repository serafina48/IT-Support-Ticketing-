# Hands-On IT Support Ticketing & ITSM Lab

A comprehensive, practical hands-on lab demonstrating IT Service Management (ITSM) concepts, ticket lifecycle management, user communication, troubleshooting documentation, and ticket escalation using Spiceworks Cloud Help Desk.

📑 Executive Summary & Objectives

The primary objective of this project is to simulate real-world IT Help Desk operations and standard operating procedures (SOPs). Through structured scenarios, this lab demonstrates proficiency in:

 Ticket Categorization & Prioritization: Correctly assigning severity levels (Low, Medium, High) based on operational impact.

 Effective Technical Communication: Writing professional, user-facing responses and clear internal technician notes.

 Escalation Workflows: Identifying boundaries between Tier 1 support and Tier 2/3 engineering, ensuring proper ticket transfers.

 Ticket Lifecycle Management: Managing tickets systematically from creation to resolution and documentation closure.

🛠️ Tools & Technologies Used

 Help Desk System: Spiceworks Cloud Help Desk

 Core Concepts: ITSM, Tier 1/2 Escalations, SLA Adherence, Ticket Documentation, Active Directory/Access Requests

🧪 Lab Scenarios & Execution

Scenario 1: Standard Hardware Support Ticket

Goal: Document and troubleshoot a hardware peripheral issue reported by an end-user.

1. Ticket Creation & Metadata

 Requester: Sharon Hall (tech)

 Subject: ⁠Monitor displaying no signal (computer 01) ⁠

 Category: ⁠Hardware⁠

 Priority: ⁠Medium
 ⁠
<img width="1207" height="614" alt="image" src="https://github.com/user-attachments/assets/d9f8385b-c2b9-4516-9ccc-a5ef71f7c8c9" />

2. Ticket Description

Device Hostname: ⁠DESKTOP-TECH-042⁠

Issue Description: Secondary left monitor is dark and no longer displaying anything.

Initial User Troubleshooting: Power toggled on monitor, power cables verified.

Location & Availability: 10th floor | Available after 10:30 AM today.

<img width="1060" height="581" alt="image" src="https://github.com/user-attachments/assets/4ee5726e-9390-403c-81ff-fcfc55c3905b" />

Scenario 2: Network Connectivity & Resolution Documentation

Goal: Troubleshoot a recurring wireless connectivity drop, apply the resolution, and maintain proper audit logs using public vs. internal notes.

1. Ticket Metadata

 Subject: ⁠[LAPTOP-01] Wi-Fi not working on laptop⁠

 Category: ⁠Network / Connectivity⁠

 Priority: ⁠High⁠

<img width="1047" height="472" alt="image" src="https://github.com/user-attachments/assets/93b922d9-725d-49bd-823b-53a75e83b125" />

 Status Workflow: ⁠Open⁠ ➔ ⁠In Progress⁠ ➔ ⁠Resolved⁠

2. Communication & Log Documentation

User Communication (Public Note):

*"Hello,

We identified that your device's Wi-Fi authentication certificate had expired. We have renewed and re-provisioned the certificate. 

Please disconnect from the corporate Wi-Fi, reconnect, and confirm if your connection is stable. Thank you!"*

<img width="1052" height="391" alt="image" src="https://github.com/user-attachments/assets/9a1092b4-7abf-4502-b134-9a21829b5139" />

<img width="1042" height="487" alt="image" src="https://github.com/user-attachments/assets/b5bc243b-f0b7-47e6-b7a8-8332d8d713cc" />

Internal Technical Note (Technician Audit Log):

[INTERNAL NOTE]⁠

Root Cause: Machine authentication certificate expired in Active Directory CA.

Action Taken: Force-renewed machine cert via Active Directory / MDM profile refresh.

Verification: Confirmed device auto-connected to corporate SSID with valid leash. Issue resolved.

<img width="1045" height="480" alt="image" src="https://github.com/user-attachments/assets/9050ee0d-38e9-4d6c-8e4b-01af5894a0f3" />
<img width="1057" height="522" alt="image" src="https://github.com/user-attachments/assets/51345e77-b6d4-4046-815c-51b890f00a50" />


Scenario 3: Access Control & Tier-2 Escalation

Goal: Handle an enterprise access request that falls outside Tier-1 permission boundaries by using standard escalation procedures.

1. Ticket Metadata

 Subject: ⁠[Access Request] Read-Only Access to Financial Database⁠

 Category: ⁠Software / Access Control⁠

 Priority: ⁠Medium⁠

 Assigned Queue: ⁠Tier-2 Database Administration (DBA)⁠

 <img width="1057" height="493" alt="image" src="https://github.com/user-attachments/assets/b11f0279-bf87-4b8f-94e9-3f6d238e1adb" />

2. Escalation Documentation

Public Escalation Note:

*"Hello,

I am escalating this ticket to the Systems & Database Administration team as this request requires elevated administrative privileges and manager authorization verification.

Escalation Details:

-User Account: ⁠shall_tech

-Requested Resource: Financial DB (Read-Only)

A DBA team member will contact you once the request has been reviewed."*

<img width="1054" height="466" alt="image" src="https://github.com/user-attachments/assets/d2353b17-110c-4451-b3a4-f7db4109c7e5" />

📌 Key Takeaways & Skills Summary

1. Structured Logging: Using standardized naming conventions (e.g., ⁠[HOSTNAME] Issue Brief⁠) speeds up technician response time.

2. Clear Separation of Notes: Keeping public notes professional and non-technical, while writing precise, technical internal notes for auditing and team collaboration.

3. Proper Escalation: Routing tickets with complete diagnostic context ensures smooth handoffs between Tier-1, Tier-2, and Tier-3 teams.

T-Support-Ticketing-
A lab for IT Support Ticketing
