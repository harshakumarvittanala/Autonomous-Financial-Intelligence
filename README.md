# SignalCore Intelligence — Autonomous Financial Research & Forensic Terminal

> **Autonomous financial intelligence engine that investigates public corporate evidence on its own to uncover non-obvious, evidence-backed financial realities.**
> 
> *Architected & Developed by **Harsha Kumar Vittanala***

---

## 🎯 Executive Overview

Financial information is scattered across thousands of disclosures: quarterly results, statutory annual report notes, investor conference call transcripts, exchange filings, peer releases, and macroeconomic benchmarks. Most conventional AI finance tools stop at mere summarization or generic chatbot Q&A.

**SignalCore Intelligence** is built for **autonomous discovery**:
- **Not a finance chatbot** → an autonomous research investigator.
- **Not a news summarizer** → uncovers hidden operational and accounting divergences.
- **Not a report generator** → actively forms, tests, and self-falsifies hypotheses.
- **Not a single-source answer** → produces a triangulated, auditable conclusion with multiple independent sources.
- **Auditable & Falsifiable** → every major claim links back to statutory document passages, with explicit future conditions that could disprove the thesis.

---

## 🔬 The 7-Stage Autonomous Pipeline

```
┌─────────────────────────────────────────────────────────────┐
│ 1. Discover Research Angles                                 │
│    Identify non-obvious operational & accounting vectors    │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 2. Retrieve Public Sources                                  │
│    Annual Reports (10-K), Decks, BSE/NSE Filings, Peers     │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 3. Extract Facts & Timeline                                 │
│    Quarterly chronology, line items & executive transcripts │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 4. Calculate Derived Relationships                          │
│    Price/Volume split, Debtor Days, CWIP Turnover, Slippage │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 5. Form Core Hypotheses                                     │
│    Synthesize non-obvious thesis distinguishing price/volume│
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 6. Search Contradictions                                    │
│    Stress-test against sector inflation & peer benchmarks   │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 7. Score Evidence & Falsify                                 │
│    Assign strength rating & define falsification criteria   │
└─────────────────────────────────────────────────────────────┘
```

---

## 📊 The 8 Mandatory Output Elements

Every discovery produced by SignalCore delivers:

1. **The Discovery**: One clear, assertive sentence describing the non-obvious finding.
2. **Why It Matters**: 3 to 5 bullet points explaining the valuation risk, balance sheet liquidity drag, or structural durability.
3. **Auditable Evidence Trail**: Independent public sources with exact citations, document period, date, and external verification links.
4. **Temporal Timeline**: Chronological progression showing when the divergence emerged and how management acknowledged it.
5. **Numbers & Calculations Engine**: Mathematical formulas and quarterly metrics tables demonstrating derived relationships.
6. **Strongest Counterargument**: The strongest alternative explanation (e.g., sector inflation, channel shift) and why the data does not fully dismiss the anomaly.
7. **Falsification Condition**: Exact quantitative future checkpoints that would cause the system to abandon or reverse its conclusion.
8. **Evidence Strength Rating**: Multi-factor scoring (`Strong`, `Moderate`, `Weak`) with audit resilience notes and limitations.

---

## 🏛️ Supported Sector Tracks

| Track | Focus | Key Inquiries |
|---|---|---|
| **Track A — Banking, NBFCs & Financials** | Asset Quality & Funding Mix | Loan-book growth vs gross slippage divergence, Credit-to-Deposit (CD) ratio surge vs CASA moderation, wholesale deposit cost escalation. |
| **Track B — Energy, Power & Renewables** | Energy Transition & Capex | Thermal EBITDA dependence vs green narrative, Capital Work-In-Progress (CWIP) to commissioned capacity turnover bottlenecks. |
| **Track C — Consumer, FMCG & Retail** | Growth Quality & Channel Health | Price-led vs volume-led revenue divergence, distributor receivable days expansion, channel inventory buildup. |
| **Track D — Pharma & Healthcare** | Portfolio Shift & Compliance | Specialty transformation vs US generic price erosion, USFDA Form 483 inspection citations hitting filings before mainstream news. |

---

## 💻 Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS, Lucide Icons, Motion
- **Backend**: Node.js, Express, Vite Server Middleware (`server.ts`)
- **AI & Forensics Engine**: Google `@google/genai` SDK (`gemini-3.8-flash`) with structured schema generation and temperature-controlled reasoning
- **Evaluation Engine**: Audited reference benchmark datasets for instant offline exploration & verification

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/harshakumarvittanala/Autonomous-Financial-Intelligence.git
cd Autonomous-Financial-Intelligence
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
PORT=3000
```

### 4. Run the Full-Stack Terminal

```bash
npm run dev
```

Open your browser at `http://localhost:3000`.

---

## 📄 License & Attribution

Architected & engineered by **Harsha Kumar Vittanala** (`harshakumarvittanala@gmail.com`).

*Disclaimer: Grounded strictly in public regulatory filings, quarterly conference call transcripts, and statutory balance sheet notes. Contains zero financial recommendations (buy/sell/hold).*
# Autonomous-Financial-Intelligence
# Autonomous-Financial-Intelligence
