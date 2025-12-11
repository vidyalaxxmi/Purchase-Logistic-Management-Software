**Purchase & Logistics Management System**
A web-based application to manage import and domestic purchases, track deliveries, manage claims, record sales, and deliver visual reports via dashboards. Centralizes purchase, shipment, claims and sales data to improve visibility, speed up resolution, and support production & supply-chain decisions.

**Key features**

1. Create & manage import and domestic purchase orders
2. Upload and store all purchase & shipping documents (PI, contract, B/L, COA, invoices, etc.)
3. Automated shipment tracking via container number / Billing / booking through integrated APIs (with manual override)
4. Claims management workflow (log claim, attach evidence, track settlement)
5. Sales recording module linked to purchases and inventory
6. Role-based access: Admin, Buyer, Supplier
7. Multi-dashboard visual analytics (procurement, logistics, financial risk, shipment timelines, detention)
8. Currency conversion (foreign → INR) and payment tracking (pre-payment, open amount, detention fees)

**Functional modules**

1. User Management: RBAC, invite flows for Buyers & Suppliers.
2. Import Form: Dynamic fields for supplier/material, vessel/container details, ETS/ETA, document uploads.
3. Domestic Form: Simplified PO flow with GST and payment terms.
4. Delivery Tracking: API-driven updates + manual tracking, milestones, container status.
5. Claims: Claim ID mapping to orders, evidence uploads, negotiation & settlement tracking.
6. Sales: Record sales transactions, link to inventory and purchases.
7. Reporting & Dashboards: KPI tiles and charts covering transit, daily/weekly orders, funds needed, detention, LME/MCX comparisons, timelines.
8. Important documents to upload per import PI, Sales Contract, Pre-payment receipt, Invoice, Packing List, COO, PSIC, FORM 9, FORM 6, Bill of Lading, Insurance, Detention receipt, COA.

**Non functional requirements**

1. Performance: support concurrent users with page loads in ~3–5s on broadband
2. Scalability: handle 100% traffic growth over 2 years
3. Security: RBAC, industry-standard protections
4. Availability: target 99.9% uptime
5. Backup & DR: daily backups, disaster recovery plan
6. Usability: responsive UI for desktop/tablet/mobile

**API & integrations**

1. Shipping carriers / forwarder APIs for container tracking
2. Currency conversion / forex API for real-time INR conversion
3. Optional: LME/MCX price feeds for dashboard KPIs
