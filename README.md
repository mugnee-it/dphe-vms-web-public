# DPHE Visitor Management System

A secure, role-based visitor management platform that streamlines check-in, approvals, and reporting for public-sector reception and security teams.

---

## Overview

Organizations that welcome visitors need more than a paper log. This solution digitizes the full visitor lifecycle—from reception intake and officer review to management oversight and audit-ready history. It is designed for environments where accountability, speed, and clear separation of duties matter.

The platform helps front-desk staff register visitors quickly, routes approval requests to the right officers, and gives administrators structured data for departments, staff, and compliance reporting—without relying on scattered spreadsheets or manual follow-up.

---

## Key Features

- **Guided visitor intake** — Reception workflows capture visit details in a consistent, efficient way.
- **Role-based access** — Separate experiences for reception, approving officers, and administrators.
- **Approval queue & decisions** — Officers can review pending visits and act with a clear audit trail.
- **Today’s queue & visit detail** — Real-time visibility into who is expected, in progress, or completed.
- **Administration** — Department and employee structure support accurate routing and reporting.
- **Operational reports** — Summaries and exports to support management and compliance needs.
- **Audit logging** — Key actions are recorded to support accountability and reviews.
- **Hosted approval links** — Token-based flows allow secure decisions without unnecessary friction.
- **Notifications** — Email and messaging channels can alert stakeholders when action is required.

---

## Industry & Use Case

**Industries:** Public sector, government departments, regulated facilities, and any organization with controlled entry and formal approval paths.

**Typical use cases:**

- Government or departmental offices with reception and security review
- Sites that require officer or manager approval before visitor access
- Teams that must demonstrate who approved access and when

---

## System Workflow

1. **Visitor arrives** — Reception registers the visit using the guided intake flow.
2. **Request routed** — The system associates the visit with the right department and approval path.
3. **Officer review** — Responsible staff see pending items in an inbox-style queue.
4. **Decision** — Approve or decline with actions reflected immediately in the live queue.
5. **Notifications** — Stakeholders are informed when relevant (e.g., approval needed or completed).
6. **Oversight** — Administrators monitor structure (departments, people) and run reports.
7. **Audit** — Important events remain available for later review and governance.

---

## Tech Stack

The production implementation combines a modern web interface with a secure API and database layer:

| Layer | Technologies |
|--------|----------------|
| **Web application** | React, Vite |
| **UI & styling** | Tailwind CSS |
| **API & services** | Node.js, Express |
| **Data** | PostgreSQL |
| **Validation & integration** | Schema validation, HTTP client libraries, transactional email and messaging integrations |

*Exact versions and internal modules are not published in this showcase.*

---

## Screenshots

Add your product images under `./screenshots/`. Suggested filenames:

| Suggested file | What to show |
|----------------|----------------|
| `./screenshots/01-login-portal.png` | Branded sign-in / secure entry |
| `./screenshots/02-reception-dashboard.png` | Reception home or today’s queue overview |
| `./screenshots/03-new-visit-intake.png` | Visitor registration or intake form |
| `./screenshots/04-officer-inbox.png` | Pending approvals queue |
| `./screenshots/05-visit-detail.png` | Single visit detail with status |
| `./screenshots/06-admin-departments.png` | Department or structure management |
| `./screenshots/07-admin-employees.png` | Employee directory or import |
| `./screenshots/08-reports.png` | Sample operational or summary report |
| `./screenshots/09-audit-logs.png` | Audit or activity history view |
| `./screenshots/10-mobile-tablet.png` | Responsive layout on phone or tablet |

Example embed (replace with your files):

![Reception dashboard](./screenshots/02-reception-dashboard.png)

---

## Architecture (High Level)

- **Client application** — A single-page web experience used by reception, officers, and admins, with routing and role-aware screens.
- **Application server** — REST-style APIs enforce authentication, authorization, and business rules.
- **Database** — Relational storage for visits, organizational data, users/roles, and audit events.
- **Integrations** — Outbound notifications and optional messaging channels connect the system to email and mobile-friendly workflows.

No implementation code, configuration, or deployment details are included in this repository.

---

## Source Code Notice

**The full source code, database schemas, deployment configuration, and internal documentation are not public.** They remain private to protect security, client confidentiality, and intellectual property.

This repository exists **only** as a **portfolio and capability showcase** for prospective clients and partners.

---

## Company

**Mugnee IT Solution**  
Website: [https://mugneeit.com](https://mugneeit.com)

We design and deliver tailored software for organizations that need reliable, secure, and maintainable systems—not generic templates.

---

## Contact

If you are planning a **visitor management**, **reception and security workflow**, or similar **operational platform**, we would welcome a conversation.

**Reach out through [mugneeit.com](https://mugneeit.com)** to discuss requirements, timelines, and how we can build a solution aligned with your policies and stakeholders.

---

*Showcase repository — no runnable application or proprietary assets included.*
