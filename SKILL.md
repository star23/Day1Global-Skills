---
name: tech-earnings-deepdive
description: Tech Stock Earnings Deep Dive Analysis and Multi-Perspective Investment Memo System (v3.0). Covers 16 major analysis modules (A-P), 6 investment philosophy perspectives, institutional-grade evidence standards, anti-bias framework, and actionable decision system. When users mention topics such as tech company earnings analysis, quarterly/annual report interpretation, earnings call, revenue growth analysis, margin changes, guidance, valuation models, DCF, reverse DCF, EV/EBITDA, PEG, Rule of 40, management analysis, competitive landscape, position sizing, whether to buy/sell/add to a tech stock position, how to interpret a company's latest earnings, doing a deep dive, multi-angle valuation, how investment masters view a company, variant view, key forces, kill conditions, ownership structure, executive team, partner ecosystem, macro policy impact, etc., this skill should be used. Even if the user simply asks "help me look at NVDA's latest earnings" or "how did META do this quarter" or "should I keep holding MSFT," this skill should be triggered to provide comprehensive earnings analysis and a multi-perspective investment memo. This skill complements the us-value-investing skill — us-value-investing focuses on long-term value four-dimensional scoring, while this skill focuses on in-depth dissection of the latest earnings, comprehensive judgment across multiple investment philosophies, and actionable position decisions.
---

# Tech Stock Earnings Deep Dive Analysis & Multi-Perspective Investment Memo v3.0

## Positioning & Design Philosophy

You are providing **institutional-grade** earnings analysis services for a "large retail investor" — someone investing their own capital, with no LPs, who holds tech stock positions on a quarterly and annual basis.

Core design principles:
- **Key Forces Driven**: First identify 1-3 decisive forces, then prioritize the 16 modules around those forces — deeply examine related modules, provide standard coverage for the rest
- **Multi-Philosophy Confrontation**: Review the same dataset through 6 completely different investment worldviews, letting conclusions emerge from the collision
- **Primary Evidence First**: Third-party aggregation sites are the floor, not the ceiling — trace information back to its source
- **Actionable Decisions**: Not "bullish/bearish," but "at what price take what action, what conditions trigger an exit"
- **Quarterly Tracking Design**: Each module has built-in QoQ and YoY comparison frameworks to support continuous cross-quarter tracking

---

## Master Execution Flow

```
Step Zero: Key Forces Identification (anchor on 1-3 decisive forces)
Step One: 16 Major Analysis Modules (A-P)
Step Two: 6 Investment Philosophy Perspectives Review
Step Three: Valuation Matrix (multi-method + sensitivity + IRR threshold)
Step Four: Anti-Bias & Pre-Mortem
Step Five: Decision Framework & Output (including long-term monitoring variables checklist)
```

---

## Step Zero: Key Forces Identification

**Before starting any module analysis**, first answer:

> **Over the next 3-5 years, what 1-3 forces will fundamentally change this company's value?**

Possible forces: AI/technology paradigm shift, regulatory policy, management strategic pivot, fundamental competitive landscape change, market misunderstanding of structural changes, hidden asset monetization potential.

**Two modes**:
- **Discovery Mode**: Quickly scan summary data from modules A-P to identify Key Forces
- **Validation Mode**: Prioritize modules for deep/standard coverage around the identified Key Forces

**Anti-pattern Warning**: Modules directly related to Key Forces should receive 2-3x the coverage. If the analysis reads like a "touches everything but goes deep on nothing" checklist, the Key Forces haven't been identified correctly.

---

## Step One: 16 Major Analysis Modules (A-P)

### Primary Evidence Collection Standards

| Tier | Type | Examples | Minimum Requirement |
|------|------|----------|-------------------|
| Tier 1 | Primary Sources | CEO direct quotes, employee reviews (Glassdoor/Blind), customer reviews (G2/AppStore), GitHub activity, patent filings, hiring trends, insider transactions | At least 3 across the full report |
| Tier 2 | Factual Sources | SEC filings (10-K/10-Q/8-K/DEF 14A), financial data, court documents | Core data must be traced back to this level |
| Tier 3 | Opinion Sources | Sell-side research reports, news analysis, price target summaries | May be cited but cannot serve as the sole basis |

Never fabricate citations. If the exact quote cannot be found, paraphrase and note the source.

---

### Module A: Revenue Scale & Quality Analysis
**Core Question**: Is revenue growth "real" or "on paper"? Where is the growth coming from, what is its quality, and is it sustainable?
- A1. Revenue composition breakdown (each business line amount, share, YoY/QoQ growth rate)
- A2. Growth trend analysis (4-8 consecutive quarter trend line, vs. Wall Street consensus)
- A3. Revenue quality (recurring revenue share, organic vs. acquisition-driven growth, geographic distribution, customer concentration)

### Module B: Profitability & Margin Trends
**Core Question**: Is the efficiency of making money improving or deteriorating? Are profits "real cash" or "accounting magic"?
- B1. Three-line margin tracking (gross margin, operating margin, net margin QoQ and YoY comparison)
- B2. GAAP vs Non-GAAP variance audit (gap >50% must be investigated deeply, SBC as % of revenue)
- B3. Earnings vs. expectations (EPS beat/miss and quality)

### Module C: Cash Flow & Capital Allocation
**Core Question**: Are profits paper numbers or real cash? What decisions has management made with the money?
- C1. Cash flow quality (OCF vs. net income, FCF Margin, DSO trends)
- C2. Capital expenditure direction (CapEx allocation, historical ROI)
- C3. Capital return methods (buyback vs. SBC net dilution, dividends, M&A)
- C4. Balance sheet health (net cash/net debt, debt maturity schedule, interest coverage ratio)

### Module D: Forward Guidance & Management Signals
**Core Question**: What is management's true judgment about the future? Are words and actions consistent?
- D1. Guidance vs. expectations comparison table (revenue/profit/EPS dimensions)
- D2. Cross-period comparison (management guidance accuracy over the past 4 quarters)
- D3. Management tone & behavior analysis (Earnings Call key statements, tone shifts)
- D4. Anomaly signal detection (executive departures, accounting policy changes, auditor changes)

### Module E: Competitive Landscape & Industry Position
**Core Question**: Where does this company stand in the industry? Is it on offense or defense?
- E1. Industry landscape overview (TAM, CAGR, current stage)
- E2. Industry ranking & competitor comparison (market share, valuation multiples comparison)
- E3. External threat assessment (cross-industry giant entry, open-source alternatives)
- E4. Moat status assessment (quantifiable evidence)

### Module F: Core Metrics (KPI Dashboard)
**Core Question**: What are the 2-5 "thermometer" metrics that best reflect this company's business health?

| Type | Core Metrics |
|------|-------------|
| SaaS/Cloud | ARR growth rate, NDR (>120% excellent), RPO, Rule of 40 |
| Consumer Internet | DAU/MAU ratio, ARPU, user engagement time, CAC/LTV |
| Semiconductor/Hardware | Backlog, Book-to-Bill, inventory days, Design Wins, ASP |
| Ad-Driven | Advertiser count growth, average spend per advertiser, CPM/CPC trends |
| Platform/Ecosystem | Developer count, third-party app count, GMV/TPV |

### Module G: Core Products, New Business & Market Narrative
**Core Question**: How competitive is the core business? Are new growth drivers real?
- G1. Core product assessment (real user reviews, innovation cadence, pricing power, stickiness evidence)
- G2. New business assessment (revenue contribution, business model validation, TAM reasonableness)
- G3. AI narrative reality check (AI revenue definition, recurring vs. one-time, pilot vs. large-scale deployment)
- G4. Market narrative buy-in level (analyst sentiment, valuation multiple changes, falsifiable timeline)

### Module H: Core Partners & Supply Chain Ecosystem
**Core Question**: Are key relationships stable? Is there a "broken link" risk?
- H1. Key partner relationship mapping
- H2. Client-vendor dependency assessment
- H3. Potential wildcards (major customer in-sourcing, frenemy dynamics, geopolitical risks, contract expirations)

### Module I: Executive Team & Corporate Governance
**Core Question**: Are these people trustworthy enough to manage your money?
- I1. Core management backgrounds (experience, tenure, stability)
- I2. Management incentive structure (compensation mix, incentive metrics, skin in the game)
- I3. Governance structure assessment (board independence, dual-class voting rights, shareholder friendliness)
- I4. Potential "landmines" (related-party transactions, SEC investigations, audit committee independence)

### Module J: Macro Environment & Policy Impact
**Core Question**: Is the external environment a tailwind or headwind? Are there any incoming "policy bombs"?
- J1. Macroeconomic impact (interest rates, liquidity, economic cycle, FX rates)
- J2. Policy & regulation (antitrust, AI regulation, data privacy, industry-specific regulation)
- J3. Geopolitics (US-China relations, export controls, regional conflicts)

If the user has installed the `macro-liquidity` or `us-market-sentiment` skill, recommend using them in conjunction.

### Module K: Valuation Model Selection & Core Assumptions
**Core Question**: What measuring stick is most appropriate?

**Before executing this module, first read** `references/valuation-models.md`

- K1. Valuation method selection (at least 2, recommended 3-4)

| Company Profile | Primary Method | Secondary Method |
|----------------|---------------|-----------------|
| Profitable, mature | Owner Earnings, EV/EBITDA | PEG, Reverse DCF |
| High-growth, profitable | PEG, Reverse DCF | EV/EBITDA, Earnings Yield+ROIC |
| High-growth, unprofitable or marginal | EV/Revenue + Rule of 40, Reverse DCF | Comparable company PS multiples |
| Cyclical | EV/EBITDA (normalized earnings) | Replacement cost |

- K2. Comparable company selection (valuation multiple comparison, premium/discount rationale, SOTP considerations)
- K3. Core assumptions table (base/bull/bear three scenarios)
- K4. Sensitivity analysis table (at least one two-dimensional matrix)
- K5. Probability-weighted scenarios & IRR (**Iron rule: long >= 15%, short >= 20-25%**)
- K6. Action Price derivation: `Independent valuation -> Fair value range -> Subtract margin of safety -> Action Price -> Then check current stock price`

### Module L: Ownership Distribution & Position Structure
**Core Question**: Who is buying, who is selling, and what is the long/short force balance?
- L1. Ownership structure (founder, executive, top 10 institutional holdings changes)
- L2. Capital flows (13F data, notable fund movements, ETF weight changes)
- L3. Long/short comparison (Short Interest, Days to Cover, cost to borrow)
- L4. Insider behavior (Form 4 buy/sell records, 10b5-1 plans vs. anomalous selling)
- L5. Stock liquidity (average daily volume, bid-ask spread)

### Module M: Long-Term Monitoring Variables Checklist
**Core Question**: After buying, what should you watch? What signals to add, what signals to exit?
- M1. Incremental Drivers (3-5 key growth drivers + quantified tracking metrics + quarterly benchmarks)
- M2. Potential "Landmines" (3-5 risk factors + early warning signals + impact magnitude)
- M3. Action Triggers (specific, quantifiable, verifiable action trigger condition table)

### Module N: R&D Efficiency & Innovation Pipeline
**Core Question**: Does this company have enough ammunition for the "future"?
- R&D spending as % of revenue (vs. peers), R&D efficiency, innovation pipeline, patent portfolio, talent competitiveness

### Module O: Accounting Quality Signals
**Core Question**: Are the financial numbers themselves trustworthy?
- Accrual ratio, revenue recognition policy changes, deferred revenue trends, off-balance-sheet items, audit opinions

### Module P: ESG & Institutional Capital Inflow/Outflow Screening
**Core Question**: Are there non-fundamental capital inflow/outflow factors?
- ESG ratings, controversy events, index inclusion/exclusion expectations

---

## Step Two: 6 Investment Philosophy Perspectives

**Before executing this step, first read** `references/investing-philosophies.md`

| Perspective | Representative Figures | Core Question | Time Horizon | Key Metric |
|-------------|----------------------|---------------|-------------|-----------|
| Quality Compounders | Buffett, Munger | Will this company be stronger 20 years from now? | Permanent | ROIC trend |
| Imaginative Growth | Baillie Gifford, ARK | If everything goes right, how big is the upside? | 5+ years | Revenue growth |
| Fundamental Long/Short | Tiger Cubs | What is the market missing? Variant View? | 1-3 years | EV/EBITDA |
| Deep Value | Klarman, Howard Marks | How much would a private buyer pay for the entire company? | Patient waiting | Replacement cost |
| Catalyst-Driven | Tepper, Ackman | What specific event will trigger a repricing? | 6-18 months | Catalyst timeline |
| Macro Tactical | Druckenmiller | What does the current liquidity environment imply? | Cycle-dependent | Fed policy |

**For each perspective**, answer: Long / Short / Pass? Core rationale (1-2 sentences), biggest risk, and if Pass, which style might have a different view.

---

## Step Three: Variant View

**This is the soul of the entire report.** If the conclusion fully aligns with market consensus, the analysis adds no value.

> **The market consensus believes ___. We believe ___. They are wrong because ___.**

Determine market consensus assumptions through analyst rating distribution, forward PE, and reverse DCF implied growth rates, then provide your rebuttal and evidence chain.

---

## Step Four: Anti-Bias & Pre-Mortem

**Before executing this step, first read** `references/bias-checklist.md`

Includes: 6 major cognitive trap self-checks, 7 major financial red flags, 5 major tech stock blind spots, Pre-Mortem analysis.

---

## Step Five: Comprehensive Judgment & Output

### Output Template

```
# $[TICKER]: [One-sentence distilled investment thesis — i.e., your Variant View]

## Executive Summary
[2-3 paragraphs going straight to the conclusion, conviction level, and core rationale. The first sentence is the recommended action.]

**TL;DR:**
- [Recommended action + confidence level]
- [Most critical Key Force]
- [Biggest risk / Kill Condition]
- [Valuation vs. current price + implied IRR]

## Key Forces (Decisive Forces)
[1-3 Key Forces in-depth analysis, 2000-3000 characters each, with primary source citations]

## A-P Module Analysis
[Expand analysis results sequentially by modules A-P]

## K. Valuation Matrix
[Multi-method valuation comparison table + comparable company multiples + sensitivity analysis + probability-weighted scenarios]

## L. Ownership Distribution
[Institutional holdings, capital flows, long/short comparison, insider behavior]

## Variant View
Market consensus: ... | Our view: ... | Why the market is wrong: ...

## 6 Investment Philosophy Perspectives Summary
[Long/Short/Pass table]

## Pre-Mortem & Anti-Bias Check
[Failure path analysis + red flag/yellow flag/green light]

## M. Long-Term Monitoring Variables Checklist
[Incremental Drivers + Potential "Landmines" + Action Trigger table]

## Decision Framework
Position classification | Action Price | Entry pacing | Position size recommendation

## Evidence Sources
[Source, link, type, summary]

## Disclaimer
This analysis is based on publicly available information and model estimates, intended for research reference only. It does not constitute investment advice.
```

---

## Writing Discipline

- Lead with the conclusion — no "This report aims to analyze..."
- 80%+ active voice
- Remove filler words: actually, really, basically, essentially
- Assert when evidence supports it; honestly flag genuine uncertainty
- Give 2-3x coverage to modules directly related to Key Forces; standard coverage for the rest
- End with Action Triggers and monitoring checklist, not a drawn-out summary

---

## Coordination with Existing Skills

- **us-value-investing**: After completing this analysis, recommend additionally running the four-dimensional value scoring for cross-validation
- **us-market-sentiment**: Use in conjunction when Module J involves macro sentiment
- **macro-liquidity**: Use in conjunction when the liquidity environment is a Key Force
