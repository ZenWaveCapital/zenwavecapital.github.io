---
layout: single
title: "ZenWave A + B Quantitative Validation Report"
permalink: /quant-report/
toc: true
toc_sticky: true
toc_label: "Sections"
author_profile: true
---

## ZenWaveCapital Quantitative Validation Report  
**Models:** ZenWave A & ZenWave B  
**Market:** USDJPY  
**Methodology:** Systematic · AI-Accelerated · Fully Automated · Anonymity by Design

ZenWaveCapital operates as an **anonymous AI-accelerated quant research lab**, using a dual-model validation workflow that mirrors the governance practices of modern institutional quant teams.

- The **primary internal AI** is used for procedural validation:  
  WFA slicing, statistical auditing, data boundary checks, leakage prevention.
- A **secondary external public AI** is used as an independent auditor to verify interpretation, methodological integrity, and bias mitigation.

This two-layer validation framework ensures **high procedural correctness**, **consistent out-of-sample behavior**, and **statistical defensibility**.

This report documents the formal validation results for ZenWave A and ZenWave B.

---

## 📐 Walk-Forward Analysis (WFA) Overview

ZenWave uses **multi-slice Walk-Forward Analysis (WFA)** as its primary robustness framework.  
Every engine must demonstrate **profitable, stable out-of-sample (OOS) behavior** across multiple distinct volatility regimes.

Validation includes:

- AI-assisted verification of slicing boundaries  
- Independent IS/OOS partitions with zero leakage  
- Equity shape & structural consistency checks  
- PF/DD stability and regime alignment  
- Parameter drift analysis  
- Dual-AI audit to reduce human bias and methodological blind spots  

This creates **institutional-grade validation rigor** and minimizes the chance of overfitting or false robustness.

---

## 🧭 A-Series WFA Timeline (Long-Term Engine)

| Slice | Role | Period     |
|-------|------|------------|
| A1    | IS   | 2014–2018  |
| A1    | OOS  | 2019–2020  |
| A2    | IS   | 2016–2020  |
| A2    | OOS  | 2021–2022  |
| A3    | IS   | 2018–2022  |
| A3    | OOS  | 2023–2024  |
| A4    | IS   | 2019–2023  |
| A4    | OOS  | 2024–2025  |

{: .notice--info}
A4 uses an extended IS window for validation only.  
**Live ZenWave A uses the full-window 2014–2025 parameter set**, confirmed stable by all A1–A4 slices.

---

## 🧭 B-Series WFA Timeline (Medium-Term Engine)

| Slice | Role | Period        |
|-------|------|----------------|
| B1    | IS   | 07/2018–2020   |
| B1    | OOS  | 2021           |
| B2    | IS   | 2019–2021      |
| B2    | OOS  | 2022           |
| B3    | IS   | 2020–2022      |
| B3    | OOS  | 2023           |
| B4    | IS   | 2021–2023      |
| B4    | OOS  | 2024           |
| B5    | IS   | 2022–2023      |
| B5    | OOS  | 2024–2025      |

{: .notice--info}
**B5 is selected for production** due to exceptional IS/OOS alignment, low fragility, and strong performance during the 2022–2025 volatility regime.

<br>

---

## 🧠 Portfolio Structure (A/B Engines)

    ZenWave Portfolio
           │
    ┌──────┴────────┬──────────────┐
    │               │              │
    │       ZenWave A              │
    │   Long-Term Breakouts        │
    │                              │
    └──────┬────────┘      ┌───────┘
           │               │
       ZenWave B (Medium-Term Breakouts)
           │
           ▼
     Combined Output

- **ZenWave A** = long-term structural breakout engine (2014–2025)  
- **ZenWave B** = medium-term adaptive breakout engine (2018–2025)  
- Combined = **multi-horizon robustness** with reduced decay risk and broader regime coverage

This structure mirrors institutional multi-horizon portfolio design.

---

## 🔐 Risk-Control Framework (A & B)

    Position Sizing (1% risk)
               │
               ▼
         Stop-Loss Logic
               │
               ▼
        Take-Profit Logic
               │
               ▼
    ┌────────────────────────────────────────────┐
    │  No Martingale                             │
    │  No Grid                                   │
    │  No Simultaneous Hedge Positions           │
    │  Reversal entries are independent signals  │
    └────────────────────────────────────────────┘
               │
               ▼
        Server-Side Execution

This mirrors **institutional risk standards**:

- No recovery trading  
- No leverage escalation  
- No offsetting hedge stacks  
- All entries independent and rule-driven  

<br>

---

# 📘 ZenWave A — Quant Validation Summary

## **Strategy Type**
Long-term USDJPY structural breakout engine (2014–2025).  
Fully automated, deterministic rules, fixed SL/TP.

## **Walk-Forward Findings (A1–A4)**

ZenWave A demonstrates:

- Fully profitable OOS behavior across all slices  
- No catastrophic regime failures  
- Stable profit factor  
- Controlled drawdowns  
- Natural parameter evolution  
- Structural consistency across 12 years  

## **AI-Assisted Validation Findings**
- All slicing boundaries verified  
- Zero data leakage  
- IS/OOS behavior shows strong structural alignment  
- Robustness ranks as **exceptional within ZenWave’s internal WFA benchmark library**  
- External AI auditor confirms methodology as statistically disciplined and institutionally sound  

## **Robustness Conclusion**
ZenWave A passes with **high institutional confidence**.  
Its full-window parameters form the **long-term backbone** of the ZenWave portfolio.

**WFA Video:** 🎥 [Watch](https://youtu.be/r2AVlHbOZV0)

<br>

---

# 📘 ZenWave B — Quant Validation Summary

## **Strategy Type**
Medium-term USDJPY breakout engine (2018–2025).  
Adaptive structural logic, deterministic execution.

## **Walk-Forward Findings (B1–B5)**

All slices produce profitable OOS performance:

- **B1** — Moderate stability  
- **B2** — Strong and balanced  
- **B3** — Weakest slice but profitable  
- **B4** — Excellent stability  
- **B5** — Best alignment with modern volatility  

## **Parameter Behavior**
- Controlled drift across slices  
- No chaotic jumps  
- Stable PF/DD characteristics  

## **AI-Assisted Validation Findings**
- Verified slicing integrity  
- No overfitting detected  
- Behavior matches expectations for a medium-horizon structural engine  

## **Robustness Conclusion**
ZenWave B passes WFA with stable OOS results.  
**B5 is selected for live deployment** due to regime alignment and low fragility.

**WFA Video:** 🎥 [Watch](https://youtu.be/XR5DyHUJmg0)

---

# 2025 Year-End Baseline (Post-Launch)

This section establishes the **official post-launch baseline** for ZenWave A and B as of **31 Dec 2025**.

## Engine Status (as of 31 Dec 2025)

| Engine | Status | Production Parameters | Notes |
|------|--------|------------------------|------|
| ZenWave A | Live | Full-window (2014–2025) | Frozen |
| ZenWave B | Live | B5 slice | Frozen |

{: .notice--info}
**Governance:** As of 31 Dec 2025, ZenWave A and B parameters are frozen.  
No parameter, risk, or logic changes are permitted outside a formal retirement or replacement decision.

---

## FPT Consistency Check  
**Backtest (Demo) vs Backtest (Live Account) vs Live Actual**

To verify execution realism, a three-way forward-performance comparison was performed:

- **Backtest (Demo Account Assumptions)** — optimistic execution envelope  
- **Backtest (Live Account Assumptions)** — conservative execution envelope  
- **Live Actual** — real execution  

### Result

Live execution remains within the conservative envelope of historical simulation.

Observed characteristics:
- Comparable trade frequency and directionality  
- Divergence primarily attributable to spread variability and execution friction  
- No structural anomalies or tail losses beyond modeled risk  

---

## Execution Realism Note

Historical replay under demo and live account assumptions can produce different outcomes due to spread dynamics, commission modeling, and fill assumptions.

For ZenWave:
- Demo backtest represents the **upper bound**
- Live-account backtest represents the **lower bound**
- Live actual represents **reality**

This relationship is expected and does not invalidate the underlying strategy logic.

---

## Transition to Forward Performance Tracking

This Quantitative Validation Report documents **what was built**, **how it was tested**, and **why it was approved for production**.

It intentionally stops short of ongoing performance reporting.

From this point forward, live behavior is documented separately through **Forward Performance Tracking (FPT)** — a structured, periodic log that compares:

- demo backtests (optimistic execution assumptions)
- live-account backtests (conservative execution assumptions)
- actual live trades

Each Forward Performance Tracking entry:
- uses the same parameters frozen at year-end 2025
- covers the same time windows
- includes full video context explaining assumptions and observations

No changes are made retroactively.

---

## Forward Performance Tracking

Live performance tracking for ZenWave A and B is published here:

👉 **[Forward Performance Tracking](/forward-performance-tracking/)**

The accompanying video explanations are available on the ZenWaveCapital YouTube channel.

---

*This separation ensures that research, validation, and live observation remain clearly defined and auditable over time.*
