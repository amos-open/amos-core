# COMING NOVEMBER 2025 — AMOS Core v0.1 — Preview Release

**AMOS Core** is the **open data infrastructure layer** for private markets.

This is our first public release — a **preview** of the data model, architecture, and philosophy behind AMOS. It is **not production-ready** and is not intended for live systems. Instead, it’s here to demonstrate our direction, invite feedback, and spark collaboration with early adopters and institutional partners.

---

## 🚀 What Is AMOS Core?

AMOS Core is the foundation of a modern operating system for private markets asset managers. It provides a shared, open-source structure for:

* **Ingesting data** from CRMs, fund administrators, ESG platforms, and spreadsheets (via ELT tools)
* **Modeling data** in a portable, open-source way using [dbt](https://getdbt.com)
* **Defining core entities** (funds, portfolio companies, investments, commitments, KPIs, ESG, etc.)
* **Reconciling IDs and relationships** across siloed systems
* **Powering downstream reporting, dashboards, APIs, and AI integrations**

---

## 📦 What’s in This Preview

This release includes:

* 📐 A **dbt project** defining a modular data schema for private markets
* 🧩 Core entity definitions: `funds`, `portfolio_companies`, `investments`, `crm_opportunities`, `financials`, `kpis`, `esg_metrics`
* 🔗 **Relationship mappings** between entities (e.g. CRM → investment reconciliation)
* ⚙️ **Adapter macros** so the model runs on PostgreSQL, Snowflake, or BigQuery
* 🌱 A repo layout ready to evolve into a working **data warehouse pipeline**

---

## 🛑 What This Is *Not*

* ❌ Not a stable schema — we expect to iterate quickly
* ❌ Not yet officially supported

---

## 🧪 Why We’re Sharing This Now

We believe the future of private markets infrastructure must be:

* **Open** — no vendor lock-in
* **Composable** — connects to existing systems
* **Transparent** — audit-ready, regulator-friendly
* **Collaborative** — built with the ecosystem, not behind closed doors

By releasing early, we want to:

* Share our thinking in the open
* Gather feedback from GPs, LPs, fund admins, and vendors
* Identify aligned pilot users and contributors

---

## 📬 Get Involved

We’re actively working with early adopters and ecosystem partners.

If you’re interested in testing, shaping, or contributing to AMOS Core:
**→ [amos.tech/contact](https://amos.tech/contact)**

Let’s build the open operating layer for private markets — together.
