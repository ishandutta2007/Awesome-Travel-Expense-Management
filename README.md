# Awesome-Travel-Expense-Management

# Awesome Travel & Expense Management

> A curated list of top Travel and Expense Management platforms — both SaaS/Hosted commercial solutions and open-source alternatives for automating expense reports, receipt capture, and spend control.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [SAP Concur](#sap-concur)
  - [Expensify](#expensify)
  - [Ramp](#ramp)
  - [Brex](#brex)
  - [Navan (TripActions)](#navan-tripactions)
  - [Zoho Expense](#zoho-expense)
  - [Spendesk](#spendesk)
  - [Pleo](#pleo)
  - [Rydoo](#rydoo)
  - [Emburse Certify](#emburse-certify)
- [Open-Source Software](#-open-source-software)
  - [Receipt Wrangler](#receipt-wrangler)
  - [WeaveLedger](#weaveledger)
  - [ezBookkeeping](#ezbookkeeping)
  - [TREK (Travel Budget Addon)](#trek-travel-budget-addon)
  - [Caravella](#caravella)
  - [My Expenses](#my-expenses)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Travel and Expense Management platforms. These are not open-source but are included as reference points for feature comparison.

### SAP Concur
**Type:** Enterprise travel and expense management  
SAP Concur is the long-standing enterprise standard for travel booking and expense reporting, deeply integrated with SAP ERP. It handles travel requisitions, booking, expense capture, policy enforcement, and reimbursement at global scale. Suited for large organizations with complex travel policies and SAP-centric IT landscapes.

### Expensify
**Type:** Expense reporting with receipt scanning  
Expensify is a widely adopted expense management platform known for its **SmartScan** receipt capture, automated expense categorization, and corporate card reconciliation. It offers a free tier for individuals and small teams, with paid plans scaling by active users. The platform includes approval workflows, accounting integrations (QuickBooks, Xero, NetSuite), and audit rules.

### Ramp
**Type:** Finance automation with corporate cards and expense management  
Ramp combines corporate cards with expense management, bill pay, and accounting automation. It offers **free** expense management and bill pay with revenue generated from card interchange, making it attractive for startups and mid-market companies. Features include receipt matching, policy enforcement, and real-time spend visibility.

### Brex
**Type:** Corporate cards and spend management  
Brex provides corporate cards with built-in expense management, receipt capture, and approval workflows. Similar to Ramp, it monetizes primarily through card interchange. Suited for venture-backed startups and scaling companies wanting integrated card and expense tooling.

### Navan (TripActions)
**Type:** Travel and expense management with booking  
Navan (formerly TripActions) combines corporate travel booking with expense management in a single platform. It offers real-time policy enforcement, automated expense reconciliation, and travel inventory from major providers. Suited for organizations wanting to unify travel booking and expense reporting.

### Zoho Expense
**Type:** Expense management within Zoho ecosystem  
Zoho Expense provides automated expense reporting, receipt scanning, mileage tracking, and approval workflows. It integrates with Zoho Books, Zoho CRM, and other Zoho products, making it a natural choice for organizations already in the Zoho ecosystem. Pricing is per-user with a free tier for small teams.

### Spendesk
**Type:** Spend management for European finance teams  
Spendesk provides corporate cards, expense management, invoice management, and approval workflows. It is primarily focused on European markets, with customers concentrated in France [citation:11]. Suited for mid-market companies wanting an all-in-one spend management solution with strong European compliance.

### Pleo
**Type:** Spend management with smart company cards  
Pleo provides smart company cards with built-in expense management. It operates across Europe (Austria, Belgium, Denmark, Finland, France, Germany, Ireland, Italy, Netherlands, Norway, Portugal, Spain, Sweden, UK) but **not in India** [citation:6]. Features include receipt capture, automated bookkeeping, and subscription management.

### Rydoo
**Type:** Travel and expense management  
Rydoo automates expense reporting and simplifies travel booking for businesses [citation:18]. The company is headquartered in Belgium and has an office in Trivandrum, India [citation:4][citation:10]. Features include expense capture, mileage tracking, policy enforcement, and reimbursement. Suited for mid-market organizations wanting a dedicated T&E tool.

### Emburse Certify
**Type:** Expense management with audit and compliance  
Emburse Certify provides expense reporting, receipt capture, and audit services. It is part of the broader Emburse suite (including Chrome River and Abacus) targeting mid-market and enterprise organizations with compliance-heavy requirements.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Travel and Expense Management tools. The open-source ecosystem is **fragmented** — most projects are personal finance trackers, group expense splitters, or travel planners with budget features rather than full enterprise T&E platforms with policy enforcement and reimbursement workflows.

### Receipt Wrangler
**Stack:** (Check repository) | **License:** Open Source  
Receipt Wrangler is a **self-hosted expense tracking solution** with a mobile app for iOS, focused on taking full control of financial data [citation:14][citation:21]. Features include sharing receipts for collaborative expense tracking, AI-powered receipt data extraction, and community-driven development. Positioned for individuals and small groups wanting self-hosted receipt management rather than enterprise policy enforcement.  
**Best for:** Users wanting a self-hosted, AI-assisted receipt manager with mobile access for personal or small-team expense tracking.

### WeaveLedger
**Stack:** Cloudflare Workers (backend) | **License:** Open Source (backend)  
WeaveLedger is expense tracking, receipt scanning, and revenue reporting for freelancers, solo founders, and small businesses who want financial data on their own server [citation:25]. The **open-source backend** can be self-hosted on Cloudflare Workers (deploy in ~5 minutes). Features include AI receipt scanning (with bring-your-own Anthropic/OpenAI key or WeaveHub AI), expense categorization, PDF expense reports with receipt images, budgets, tax estimates, P&L reports, and bank statement matching. The mobile app is free with a Pro subscription for advanced features.  
**Best for:** Freelancers and solo founders wanting self-hosted expense tracking with AI receipt scanning and revenue reporting, accepting the Cloudflare Workers deployment model.

### ezBookkeeping
**Stack:** Go / SQLite/MySQL/PostgreSQL / Docker | **License:** Open Source  
ezBookkeeping is a lightweight, self-hosted **personal finance app** with a focus on bookkeeping features [citation:2]. Features include receipt image recognition (AI-powered), MCP support for AI integration, two-level accounts and categories, location tracking, multi-currency support, 2FA, and data import/export in many formats. Runs on low-resource devices including Raspberry Pi and NAS. While **not a corporate T&E tool**, it provides robust expense tracking for individuals wanting self-hosted financial control.  
**Best for:** Individuals wanting a lightweight, self-hosted personal bookkeeping app with receipt OCR and multi-currency support.

### TREK (Travel Budget Addon)
**Stack:** Node.js / React / SQLite / Docker | **License:** AGPL-3.0  
TREK is a self-hosted, real-time collaborative **travel planner** with a built-in **Costs addon** for expense tracking [citation:7][citation:9]. The Costs addon provides category-based expenses with pie charts, per-person/per-day splitting, and multi-currency support. TREK is designed for group trip planning rather than corporate expense reimbursement — it helps a group track what a trip costs and who owes what. Features include itinerary planning, reservations, packing lists, and document management.  
**Best for:** Groups planning trips together who want collaborative budget tracking alongside itinerary planning, not corporate T&E compliance.

### Caravella
**Stack:** Flutter (multi-platform) | **License:** Open Source  
Caravella is a **group expense management** app for trips, shared costs, and events . Features include group management, expense tracking with participant assignments, receipt scanning with OCR (on-device), automatic debt calculation (who owes what to whom), and CSV/JSON export. All data is stored locally on-device with no cloud sync required. Multi-platform (Android, iOS, Web, Desktop) via Flutter.  
**Best for:** Groups wanting privacy-first, on-device expense splitting for trips and shared living situations, without server infrastructure.

### My Expenses
**Stack:** Android (native) | **License:** Open Source  
My Expenses is a privacy-friendly **personal finance manager** for Android with open-source transparency [citation:8]. Features include daily expense and budget tracking, investment and portfolio management, smart receipt scanning (OCR), bank integration (FinTS for Germany), and a local web interface for desktop access. Premium features (via Contrib/Extended/Professional keys) add cloud sync, PDF exports, and advanced investment tracking.  
**Best for:** Android users wanting a feature-rich, privacy-focused personal expense tracker with OCR and optional bank sync, not corporate T&E.

---

## 📊 Comparison at a Glance

| Software | License | Type | Receipt OCR | Policy/Approval | Self-Hosted | Best For |
|----------|---------|------|-------------|-----------------|-------------|----------|
| **SAP Concur** | Proprietary | Enterprise T&E | ✅ | ✅ | ❌ | Large enterprise + SAP |
| **Expensify** | Proprietary | Expense reporting | ✅ SmartScan | ✅ | ❌ | SMB to mid-market |
| **Ramp** | Proprietary | Cards + expenses | ✅ | ✅ | ❌ | Startups (free) |
| **Brex** | Proprietary | Cards + expenses | ✅ | ✅ | ❌ | Venture-backed startups |
| **Navan** | Proprietary | Travel + expense | ✅ | ✅ | ❌ | Unified travel booking + T&E |
| **Zoho Expense** | Proprietary | Expense management | ✅ | ✅ | ❌ | Zoho ecosystem |
| **Spendesk** | Proprietary | Spend management | ✅ | ✅ | ❌ | European mid-market |
| **Pleo** | Proprietary | Cards + expenses | ✅ | ✅ | ❌ | European SMBs (not India) |
| **Rydoo** | Proprietary | T&E management | ✅ | ✅ | ❌ | Mid-market (Belgium HQ) |
| **Receipt Wrangler** | Open Source | Receipt tracking | ✅ AI | ❌ | ✅ | Self-hosted receipt management |
| **WeaveLedger** | Open Source | Freelancer expenses | ✅ AI | ❌ | ✅ (Cloudflare) | Freelancers + revenue |
| **ezBookkeeping** | Open Source | Personal bookkeeping | ✅ AI | ❌ | ✅ | Personal finance |
| **TREK** | AGPL-3.0 | Travel planner + costs | ❌ | ❌ | ✅ | Group trip budgets |
| **Caravella** | Open Source | Group expense split | ✅ OCR | ❌ | ✅ (local) | On-device group splitting |
| **My Expenses** | Open Source | Personal finance | ✅ OCR | ❌ | ✅ (local) | Android personal tracking |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Travel or Expense Management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem for **enterprise T&E with policy enforcement and reimbursement workflows** is essentially nonexistent — available projects focus on personal finance, group expense splitting, or receipt management. No open-source tool currently replicates SAP Concur or Expensify's corporate compliance features.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
