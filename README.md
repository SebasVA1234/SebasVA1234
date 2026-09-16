## Sebastián Vásquez Armas

**Data scientist and software engineer.** I build the whole path from a production
database to a decision someone actually makes: extraction, modeling, dashboards,
and the automation that keeps them alive.

Mechatronics engineer by training, currently completing an MSc in Data Science and
Machine Learning. I lead innovation and the software portfolio at a flower exporter
in Quito, Ecuador.

📍 Quito, Ecuador · [LinkedIn](https://www.linkedin.com/in/sebastian-vasquez-armas) · sebasshva@gmail.com

---

### What I actually do

At **Ecualand Farms** (flower exporter — Projects & Innovation Supervisor, CIO of
Innovation, Apr 2024 – present) I designed and implemented the company's analytics
flow end to end:

- **Extraction** straight from the production PostgreSQL database over an SSH tunnel.
- **Modeling and parameterization** in Power BI, published to the service with
  scheduled refresh.
- **Written up as the company's official procedure**, so the rest of the team creates
  and edits reports without going through me.

That last point is the one I care about. A pipeline that only its author can operate
is a liability, not an asset.

Sales, production and logistics data now feed the dashboards that management and the
commercial team use to set prices, prioritize customers and control shipments. I also
lead the ERP/CRM integration (Odoo), process automation in Python, and the technology
portfolio — defining scope and acceptance criteria, managing external vendors, and
closing low-return initiatives to move the budget somewhere it pays off.

One I'm quietly proud of: redesigning the corporate email architecture as a hybrid
forward-only model with centralized SMTP authentication, which removed the POP3
dependency and took server-side storage to zero.

---

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [export-intensity-benchmark](https://github.com/SebasVA1234/export-intensity-benchmark) | A model that scores R² = 0.94 and is worth nothing — and the leave-one-country-out evaluation that shows why. Panel of five flower-exporting economies, 1962–2023, built from the World Bank API. The finding is negative and that is the point. | Python · pandas · scikit-learn · Matplotlib |
| [powerbi-report-viewer](https://github.com/SebasVA1234/powerbi-report-viewer) | Internal operations platform: Power BI report portal plus HR, payroll, document management and air freight quoting, behind one authentication and permission layer. 136 REST endpoints, TOTP two-factor, JWT that fails closed, role-based access with per-user overrides and an audit log. | Node.js · Express · SQLite/PostgreSQL |
| [data-science-workshops](https://github.com/SebasVA1234/data-science-workshops) | Three reproducible pipelines from the MSc: vectorized operations over a territorial dataset; multi-source integration with layered storage and a seven-finding quality diagnosis; and an analytical flow that runs end to end with one command. | Python · pandas · NumPy · Jupyter |
| [txt-to-excel-fastapi](https://github.com/SebasVA1234/txt-to-excel-fastapi) | Turns unstructured text exports into clean spreadsheets. Containerized, with time-limited sharing links signed and passed in the URL fragment so they never reach server logs. | FastAPI · pandas · Docker |
| [commission-calculator-api](https://github.com/SebasVA1234/commission-calculator-api) | REST service for shipping commissions and totals, with environment-configured Basic auth and session expiry. | Java 21 · Spring Boot 3 · Docker |

### Work I can't open-source

The strongest engineering I've done belongs to the companies I did it for, so it
lives in private repositories. Happy to walk through any of it in an interview:

- **Legal-tech SaaS for trademark surveillance** — watches 174,726 Ecuadorian
  trademark registrations for conflicting filings, built on a phonetic matching
  engine, and drafts the opposition documents. FastAPI, layered architecture, Docker, CI,
  threat model documented against Ecuador's data protection law.
- **WhatsApp-first CRM for law firms** — shared inbox, matters, pipelines and
  no-code automations on the official WhatsApp Business Cloud API. Next.js,
  Supabase, deployed as a single container.

---

### Stack

- **Data** — Python (pandas, NumPy, Matplotlib), SQL, PostgreSQL, extraction from production databases over SSH tunnels
- **Machine learning** — supervised and unsupervised: regression, classification, clustering; data cleaning and preparation; exploratory analysis; honest model validation
- **BI** — Power BI (data modeling, parameters, service publishing, scheduled refresh), Tableau, advanced Excel
- **Engineering** — FastAPI, Node.js/Express, Spring Boot, Docker, ERP/CRM integration (Odoo)
- **Ways of working** — requirements gathering and acceptance criteria, vendor management, technical documentation, AI-assisted development

---

### Education and credentials

- **MSc in Data Science and Machine Learning** — Universidad Internacional del
  Ecuador, 2026 – Jun 2027 (in progress)
- **GCI World 2026** — Data Science and Machine Learning program, **University of
  Tokyo (Matsuo & Iwasawa Lab)**, Sep – Dec 2026, in progress. Taught entirely in
  English, in Python.
- **Google AI Professional Certificate** (2026) · **Google Project Management
  Professional Certificate** (2026)
- **Cisco Networking Academy** — Data Analytics Essentials · Python Essentials 1 & 2 (2026)
- **BSc in Mechatronics Engineering** — Universidad Internacional del Ecuador,
  powered by Arizona State University, 2019 – 2024. Full merit scholarship from the
  first semester, final GPA 87.96/100. Thesis graded 98.50/100: design and
  construction of a bottle packaging machine — CAD, component selection, PLC
  programming and commissioning.

### Publications and talks

- Technical article accepted — **Escuela Politécnica Nacional**, vol. 54 no. 2 (2024).
- Speaker — **I CIMITC**, Universidad de Guayaquil (June 2022).

---

*Spanish native · professional working proficiency in technical English; currently
doing a graduate program taught entirely in English.*
