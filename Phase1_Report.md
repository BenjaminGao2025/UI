# CSCI 7850 Project - Phase 1: Problem to Prototype

## 1. Problem Discovery
**Description and Motivation:**
Small and medium-sized businesses (SMBs) heavily rely on functional IT infrastructure (Wi-Fi, printers, emails, file sharing), yet they often cannot afford dedicated in-house IT departments. When a technical issue arises, business owners face immense frustration trying to find reliable, fast, and transparent IT support. Existing solutions, such as calling ad-hoc repair technicians, are often slow, lack SLA (Service Level Agreement) commitments, and offer poor visibility into the resolution progress. Our motivation is to bridge this gap by providing an "IT Butler" service—a centralized, subscription-based IT management platform that guarantees response times and proactive system monitoring for SMBs.

**Existing Solutions and Shortcomings:**
- **Ad-hoc local repair shops:** These shops require clients to bring in hardware, which disrupts business operations. They operate on a "break-fix" model rather than proactively preventing issues.
- **Enterprise-level Managed Service Providers (MSPs):** Traditional MSPs use outdated ticketing systems that are clunky, hard for non-technical users to navigate, and too expensive for small businesses.
*Gap Identified:* There is a lack of a modern, mobile-friendly interface tailored for non-technical SMB owners that clearly displays ticket status, SLAs, and overall IT health in an easily digestible format.

## 2. Solution
**Core Idea:**
"Computer Butler" is a dual-interface platform that connects SMB owners with dedicated IT professionals. It acts as a Virtual IT Department, offering a frictionless ticketing system for clients and a prioritized, SLA-driven dashboard for IT support technicians.

**Primary Features:**
1. **One-Tap Issue Reporting:** Users can quickly submit a ticket with photos, voice notes, and text.
2. **Real-time SLA Tracking & Status:** Clients see an exact countdown or ETA for when their issue will be resolved, along with live status updates (Open, Assigned, In Progress, Resolved).
3. **Monthly IT Health Reports:** Automated, easy-to-read dashboards showing device health, backup status, and security risks.
4. **Technician Triage Board:** A Kanban-style board for IT providers to manage tickets based on SLA urgency and contract scope.

**Why it's better:**
Unlike generic ticketing systems (like Jira or Zendesk), this solution is specifically tailored to the B2B IT support workflow. It removes technical jargon from the client's view, emphasizing transparency (SLAs, quotes, health scores) while giving technicians the tools they need to prioritize tasks efficiently. 

**Context of Use:**
- **Clients (Business Owners):** Will primarily use the mobile interface on the go, in their office, or at home when an IT crisis occurs.
- **Technicians (Butlers):** Will use the desktop web application in an office or remote work setting to manage multiple client networks.

**Platform:**
A responsive Web App (optimized for Mobile for clients, and Desktop for technicians).

## 3. Personas

### Persona 1: The Frustrated Business Owner (Client)
- **Name:** Mr. Chen
- **Age:** 45
- **Biography:** Founder of a local trading company with 12 employees. He is an expert in logistics and sales but knows very little about computers. He just wants things to work so his team can do their jobs.
- **Goals and Motivations:** Minimize downtime. Ensure his company's data is secure without having to understand the technical details.
- **Pain Points and Frustrations:** Gets stressed when the office printer stops working or the network goes down. Hates waiting for hours without knowing when the "IT guy" will show up.
- **Context of Use:** Uses his smartphone heavily. Needs to report issues quickly from the office floor without sitting down at a computer.

### Persona 2: The Efficient IT Technician (Butler)
- **Name:** Ben
- **Age:** 28
- **Biography:** A seasoned IT professional running an outsourced IT support agency for multiple local businesses. He is highly organized but often overwhelmed by clients texting or calling him at all hours.
- **Goals and Motivations:** Streamline client requests into one central queue. Fulfill SLA commitments to maintain monthly retainer contracts.
- **Pain Points and Frustrations:** Clients send vague problem descriptions ("the internet is broken"). Needs an easy way to triage whether an issue can be fixed remotely or requires an on-site visit.
- **Context of Use:** Uses a multi-monitor desktop setup at his home office. Needs to see a bird's-eye view of all incoming tickets and expiring SLAs.

## 4. Scenarios

1. **Scenario 1: Reporting an Urgent Issue (Client)**
   Mr. Chen’s office printer stops working, halting a major shipment. He opens the mobile app, taps "Report an Issue," snaps a photo of the error code, and selects "High Urgency." He instantly receives an SLA commitment that a technician will respond within 30 minutes.

2. **Scenario 2: Triaging a New Ticket (Technician)**
   Ben is looking at his desktop dashboard. A new ticket from Mr. Chen pops up with a 30-minute SLA countdown. Ben sees the attached photo, realizes it's a simple driver issue, and clicks "Start remote session" to fix it immediately.

3. **Scenario 3: Viewing Monthly Health Report (Client)**
   At the end of the month, Mr. Chen receives a notification. He opens the app and sees his "June IT Health Report" with a grade of B+. He notices a warning that 3 of his computers lack backups.

4. **Scenario 4: Upgrading a Service Plan (Client)**
   After seeing the backup warning in the Health Report, Mr. Chen clicks "Compare service plans." He reviews the "Standard" plan which includes backup monitoring, and taps "Request a quote."

5. **Scenario 5: Sending a Customized Quote (Technician)**
   Ben receives Mr. Chen's request for the Standard plan. On his desktop, Ben navigates to the "Projects/Quotes" tab, selects the Standard plan, applies a 10% "Founding Client" discount, and sends the interactive quote back to Mr. Chen.

6. **Scenario 6: Tracking Ticket Progress (Client)**
   Mr. Chen submitted a ticket for an email sync issue 2 hours ago. He opens the app and checks the "Ticket Detail" page. The status bar shows "In Progress" and the timeline indicates Ben has been working on it remotely for 15 minutes.

7. **Scenario 7: Reviewing Client Inventory (Technician)**
   Ben receives a call from a client asking if their front desk PC needs an upgrade. Ben opens the "Clients" tab, selects their profile, and views the "Device Inventory" table to check the hardware specs and last maintenance date.

8. **Scenario 8: Managing Out-of-Scope Requests (Technician)**
   A client submits a request to set up a brand-new office network. Ben’s dashboard flags this as an "Out of contract scope" project request. Ben reviews the request and clicks "Send estimate" to bill this as a separate project outside the monthly retainer.

---
*Note for submission: Combine this text with the Low-Fidelity wireframe screenshots (Task 5) and hand-drawn storyboards (Task 6) into your final Word/PDF document.*
