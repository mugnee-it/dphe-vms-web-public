# Visitor Management System — Jalalabad Gas Transmission & Distribution System Limited

A secure, role-based visitor operations portal for reception, approving officers, and HR administration—covering intake, multi-channel notifications, gate check-in/checkout, reporting, and audit-ready activity history.

---

## Overview

**Jalalabad Gas Transmission and Distribution System Limited** needed a dependable way to move beyond manual visitor logs: clear accountability, faster front-desk service, and controlled entry tied to officer approval.

This engagement delivers a **tailored visitor management experience**—not an off-the-shelf template. Reception can register visitors efficiently; destination officials receive requests promptly; and HR administrators maintain organizational structure, run operational reports, and review system activity in one place.

The same concepts apply to other **utilities, regulated sites, and public-sector offices** that require structured visitor flow and evidence of who approved access, and when.

---

## Key Capabilities

- **Secure, role-based sign-in** — Separate workspaces for reception, officers, and administrators.
- **Reception-led registration** — Guided intake captures identity, contact, purpose, scheduling, destination official, and guest-card linkage where required.
- **Self-service visitor entry (QR)** — Visitors can submit requests from their own device after scanning a reception QR code—no visitor account required—while reception can still enter visits manually when preferred.
- **Officer review & decisions** — Pending requests surface in an officer inbox; visits can be approved or rejected with notes and timing adjustments.
- **Multi-channel awareness** — Alerts reach officials through the application together with **email and WhatsApp**, so action is less likely to be missed.
- **Gate-ready check-in/checkout** — After approval, reception can verify the visitor and progress the visit using clear status and gate actions.
- **HR administration** — Employees, departments, and bulk import support keep routing and ownership accurate.
- **Reporting & export** — Filter visits by date, status, department, and host; export results for analysis and documentation (spreadsheet-friendly formats).
- **Audit logging** — Administrative and data changes are recorded to support transparency and reviews.

---

## Industry & Use Case

**Primary context:** Energy and infrastructure—**gas transmission and distribution**—with the security and process discipline typical of large operational sites.

**Broader fit:** Government departments, utilities, industrial campuses, and any organization that combines **public-facing reception**, **manager or officer approval**, and **audit expectations**.

---

## How the Process Works

1. **Arrival** — The visitor is registered at reception **or** submits details via **QR-based self-service**.
2. **Routing** — The request is tied to the correct **department** and **destination official**.
3. **Awareness** — The officer is notified through the **dashboard**, **email**, and **WhatsApp**.
4. **Decision** — The officer **approves or rejects** the visit (with optional notes). Secure **approval links** can support decision-making without friction.
5. **Gate control** — After approval, reception completes **check-in** using the assigned guest card flow; checkout completes the visit when the person leaves.
6. **Oversight** — HR administrators manage **employees and departments**, run **reports**, and review **audit history** for accountability.

---

## Delivery Approach (Why This Stands Out)

- **Built around your workflow** — Scope and screens follow the organization’s real reception and approval process—not a generic product bolted on after the fact.
- **No recurring subscription pitch for this class of delivery** — Structured as a **one-time solution** rather than an open-ended SaaS fee model (details agreed per engagement).
- **Continuity** — Post-delivery support can cover changes, maintenance, and enhancements as needs evolve.
- **Ownership** — Clients can receive **full source code** for the delivered system where that is part of the commercial agreement (the **public GitHub repo here is not a code drop**; see below).

---

## Technology Summary

| Area | Approach |
|------|-----------|
| **Web experience** | Modern single-page application (**React**, **Vite**) |
| **Interface** | Responsive, component-driven UI (**Tailwind CSS**) |
| **Services** | **Node.js** with **Express** APIs |
| **Data** | **PostgreSQL** for relational records and history |
| **Quality & integrations** | Validated payloads; email and messaging integrations for notifications |

*Version pins and internal modules are not published in this showcase.*

---

## Interface Gallery

Screens below are taken from the same materials prepared for the client (proposal / solution documentation).

### Sign-in

Secure entry for reception, officer, and admin roles.

![Secure login — role-based access](./screenshots/01-login-portal.png)

### Reception — today’s queue

Same-day visits with search, status filters, and quick access to each record.

![Today’s visitor queue](./screenshots/02-today-queue-reception.png)

### Reception — new visit intake

Structured capture of visitor profile, purpose, timing, photo, RFID/guest card, and destination routing.

![New visit registration](./screenshots/03-new-visit-intake.png)

### Officer — visit review

Review submitted details, adjust timing if needed, add notes, approve or reject.

![Officer visit review and decision](./screenshots/04-officer-visit-review.png)

### Notifications

Officials receive concise alerts with enough context to act—including paths to approve or decline securely.

![Sample approval notification](./screenshots/05-approval-notification-sample.png)

### Reception — visitor detail & gate actions

Approved visits move forward with clear **check-in / check-out** guidance at the desk.

![Visitor detail with check-in](./screenshots/06-visitor-detail-check-in.png)

### Administration — employees

Directory maintenance with search, department scope, and safe edit/delete controls.

![Employee administration](./screenshots/07-admin-employees.png)

### Administration — departments

Create and maintain departments that drive routing and reporting.

![Department administration](./screenshots/08-admin-departments.png)

### Reports

Filter by date range, status, department, and host; run the report and export for offline use.

![Reports and export](./screenshots/09-reports-and-export.png)

### Audit logs

A chronological view of important system and data events for governance.

![Audit logs](./screenshots/10-audit-logs.png)

---

## Architecture (High Level)

- **Browser application** — Role-aware navigation and forms; optimized for daily reception and officer use.
- **API layer** — Authenticated access, authorization by role, and consistent business rules for visits and administration.
- **Database** — Relational model for visitors, org structure, users, reporting, and audit events.
- **Notifications** — Connectors for email and WhatsApp (and similar channels as agreed) so approvals are visible outside the browser.

No implementation source, configuration secrets, or deployment artifacts appear in this repository.

---

## Further Documentation

A **full written proposal / solution overview** for this project—including narrative, workflow detail, and the figure captions above—is available in the repository as:

`docs/Visitor Management System.docx`

---

## Source Code Notice

**The implementation source code, database definitions, environment configuration, and private deployment details are not published here.** They are withheld for **security**, **client confidentiality**, and **commercial** reasons.

This repository is a **portfolio and capability showcase** only. Technical depth and references under NDA are shared directly with serious prospects.

---

## Company

**Mugnee IT Solution**  
Website: [https://mugneeit.com](https://mugneeit.com)

We design and deliver tailored software when organizations need reliability, security, and a product that matches how they actually work.

---

## Contact

If you are evaluating a **visitor management** initiative, **reception and gate workflows**, or a similar **operations portal**, we welcome a conversation.

**Contact us through [mugneeit.com](https://mugneeit.com)** to discuss scope, timelines, and a delivery model that fits your stakeholders and policies.

---

*Showcase repository — illustrative screenshots and documentation only; no runnable application or proprietary credentials included.*
