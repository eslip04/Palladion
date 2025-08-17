# Palladion

**Tagline:** *The Safeguard of Trust.*

Palladion is the **modern safeguard for client trust and escrow accounting** — delivering transparency, compliance, and security with the wisdom of Athena and the strength of myth.  

🌐 **Official Site:** [palladionapp.com](https://palladionapp.com)

---

## 🌐 Brand Identity
- **Name Origin:** In Greek mythology, a *Palladion* was a sacred object of Athena that guaranteed the protection of a city as long as it was preserved within its walls.  
- **What It Conveys:** Safety, endurance, wisdom, and inviolable trust.  
- **Tone:** Authoritative, timeless, secure.  
- **Visual Identity:**  
  - **Colors:** Deep navy + bronze/gold accents (authority + security)  
  - **Iconography:** Stylized shield, temple, or abstract Athena motif  
  - **Style:** Modern fintech minimalism + mythic gravitas  

---

## 🎯 Value Proposition
**For Law Firms:**  
- Eliminate manual reconciliations and compliance headaches  
- Automate client reporting and regulatory requirements  
- Reduce risk of commingling or overdrafts with enforced guardrails  

**For Clients:**  
- Real-time visibility into funds held in trust  
- Verified, downloadable monthly statements  
- Confidence that deposits and disbursements are transparent and secure  

**For Regulators & Auditors:**  
- Immutable, audit-ready logs of every transaction  
- Configurable jurisdiction profiles (IOLTA rules, statement cadence, retention)  
- Secure, dual-controlled disbursement workflows  

---

## 🚀 What It Does (MVP)
- Creates **segregated trust sub-ledgers per client** under a firm’s master IOLTA/trust account  
- **Daily bank sync** + automated **three-way reconciliation**  
- **Client portal** with real-time balances and statements  
- **Firm dashboard**: balances, disbursements, alerts, reconciliation status  
- **Compliance rails**: no commingling, no negative balances, dual approval for disbursements  
- **Audit log**: immutable WORM ledger  

---

## 🧑‍⚖️ Dashboards
### Law Firm Console
- Header cards: Total Trust | Clients with Funds | Reconciliation Status | Alerts  
- Client table: Client | Matter | Balance | Pending Disbursements | Flags  
- Actions: Reconcile | Generate Statements | Approve Disbursement | Invite Client  

### Client Portal
- Balance card with verification badge  
- Activity feed of deposits/disbursements  
- Download monthly statements (PDF, CSV)  
- Secure messaging + disbursement requests  

---

## 🧱 Suggested Tech Stack
- **Frontend:** Next.js (React), TypeScript, Tailwind  
- **Backend:** Node.js (NestJS/Express) or Python (FastAPI)  
- **DB:** PostgreSQL + Prisma/SQLAlchemy  
- **Banking API:** Treasury Prime / Unit / Stripe Treasury  
- **Identity/KYC:** Persona or Alloy  
- **Email/PDF:** Postmark/SendGrid + WeasyPrint/ReportLab  
- **Auth:** OAuth 2.1 / OIDC with RBAC  
- **Infra:** Docker, Terraform, Vercel/Fly.io + managed Postgres  

---

## 🔐 Compliance & Controls
- Immutable audit log (WORM)  
- Jurisdiction-aware profiles (IOLTA, retention, interest routing)  
- No negative client balances enforced at ledger level  
- Dual-approval workflows for disbursements above threshold  
- Field-level encryption for PII; all secrets in KMS  

---

## 📊 Market Opportunity

### 🎯 Target Market
- **Primary:** Small-to-mid-sized law firms managing client trust/IOLTA accounts  
- **Secondary:** Large firms, escrow providers, real estate attorneys, title companies  
- **Expansion:** Any industry vertical requiring third-party fund custody with compliance (e.g. property management, M&A escrow, IP transactions)  

### 💰 Total Addressable Market (TAM)
- There are **450,000+ law firms** in the U.S. alone, most required to hold client funds in IOLTA/trust accounts.  
- Estimated **$200B+** flows through attorney trust accounts annually.  
- Current solutions are outdated (manual reconciliations, spreadsheets, generic accounting software) → high risk of compliance breaches.  
- **Palladion’s TAM** = ~$3–5B annually in trust accounting + escrow software + BaaS infrastructure fees.  

### 📈 Market Tailwinds
- Increasing regulatory scrutiny of IOLTA compliance  
- Growing client demand for transparency and digital access  
- Rise of Banking-as-a-Service APIs enabling sub-account escrow models  
- Broader legaltech adoption in small/mid-size firms  

---

## 📦 Repo Structure
- `PROMPT.md` — build-ready product + engineering spec  
- `docs/wireframes.md` — page-by-page layout notes  
- `db/schema.sql` — starter schema  

---

## ⚠️ Disclaimer
Palladion is **not a bank**; it integrates with licensed bank partners. This material is **not legal advice** — compliance must be configured per jurisdiction.  

🌐 Learn more: [palladionapp.com](https://palladionapp.com)
