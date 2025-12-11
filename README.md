Purchase & Logistics Management System

A web-based application to manage import and domestic purchases, track deliveries, manage claims, record sales, and deliver visual reports via dashboards. Centralizes purchase, shipment, claims and sales data to improve visibility, speed up resolution, and support production & supply-chain decisions.

Quick link

Detailed Business Requirement Document: 

Business_Requriement_Document

Key features

Create & manage import and domestic purchase orders

Upload and store all purchase & shipping documents (PI, contract, B/L, COA, invoices, etc.)

Automated shipment tracking via container number / B/L / booking through integrated APIs (with manual override)

Claims management workflow (log claim, attach evidence, track settlement)

Sales recording module linked to purchases and inventory

Role-based access: Admin, Buyer, Supplier

Multi-dashboard visual analytics (procurement, logistics, financial risk, shipment timelines, detention)

Currency conversion (foreign → INR) and payment tracking (pre-payment, open amount, detention fees)

Functional modules

User Management: RBAC, invite flows for Buyers & Suppliers.

Import Form: Dynamic fields for supplier/material, vessel/container details, ETS/ETA, document uploads.

Domestic Form: Simplified PO flow with GST and payment terms.

Delivery Tracking: API-driven updates + manual tracking, milestones, container status.

Claims: Claim ID mapping to orders, evidence uploads, negotiation & settlement tracking.

Sales: Record sales transactions, link to inventory and purchases.

Reporting & Dashboards: KPI tiles and charts covering transit, daily/weekly orders, funds needed, detention, LME/MCX comparisons, timelines.

Important documents to upload per import

PI, Sales Contract, Pre-payment receipt, Invoice, Packing List, COO, PSIC, FORM 9, FORM 6, Bill of Lading, Insurance, Detention receipt, COA.

Non-functional requirements (summary)

Performance: support concurrent users with page loads in ~3–5s on broadband

Scalability: handle 100% traffic growth over 2 years

Security: RBAC, industry-standard protections

Availability: target 99.9% uptime

Backup & DR: daily backups, disaster recovery plan

Usability: responsive UI for desktop/tablet/mobile

Suggested tech stack (example)

Frontend: React (or Vue)

Backend: Node.js / Express or Django / FastAPI

Database: PostgreSQL or MySQL

Auth: JWT / OAuth + RBAC

Storage: S3-compatible object store for docs

Queues: RabbitMQ / Celery for background tasks (tracking updates)

Visualization: Charting library (Recharts / Chart.js / D3)

API & integrations

Shipping carriers / forwarder APIs for container tracking

Currency conversion / forex API for real-time INR conversion

Optional: LME/MCX price feeds for dashboard KPIs

Getting started (developer)

Clone the repo

Install backend & frontend dependencies

Create .env with DB and API keys

Run DB migrations and seed masters (suppliers, materials, roles)

Start backend and frontend servers
(Provide project-specific scripts and exact commands in repo when implemented.)
