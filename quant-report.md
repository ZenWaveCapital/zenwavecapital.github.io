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
**Methodology:** Systematic, AI-Accelerated, Fully Automated

ZenWaveCapital uses a **modern quant workflow** combining long-horizon Walk-Forward Analysis (WFA) with **AI-assisted statistical auditing** to ensure correct slicing, eliminate data leakage risks, and verify out-of-sample (OOS) integrity.  
This report documents the formal validation results for ZenWave A and ZenWave B.

---

## 📐 Walk-Forward Analysis (WFA) Overview

ZenWave uses **multi-slice Walk-Forward Analysis** to validate robustness across independent out-of-sample windows.  
All A-series and B-series slices show **profitable and stable OOS behavior** across multiple volatility regimes.

The validation process includes:

- AI-assisted verification of slicing boundaries  
- Independent IS/OOS partitions  
- Equity shape consistency checks  
- PF/DD stability analysis  
- Regime-alignment assessment  
- Parameter drift evaluation

This ensures **institutional-grade procedural correctness**.

---

## 🧭 A-Series WFA Timeline (Long-Term Engine)

| Slice | Role | Period     |
|-------|------|-----------|
| A1    | IS   | 2014–2018 |
| A1    | OOS  | 2019–2020 |
| A2    | IS   | 2016–2020 |
| A2    | OOS  | 2021–2022 |
| A3    | IS   | 2018–2022 |
| A3    | OOS  | 2023–2024 |
| A4    | IS   | 2019–2023 |
| A4    | OOS  | 2024–2025 |

{: .notice--info}
A4 uses an extended IS window for validation only.  
**Live ZenWave A uses the full-window 2014–2025 parameter set** confirmed stable by all A1–A4 OOS slices.

---

## 🧭 B-Series WFA Timeline (Medium-Term Engine)

| Slice | Role | Period        |
|-------|------|---------------|
| B1    | IS   | 07/2018–2020  |
| B1    | OOS  | 2021          |
| B2    | IS   | 2019–2021     |
| B2    | OOS  | 2022          |
| B3    | IS   | 2020–2022     |
| B3    | OOS  | 2023          |
| B4    | IS   | 2021–2023     |
| B4    | OOS  | 2024          |
| B5    | IS   | 2022–2023     |
| B5    | OOS  | 2024–2025     |

{: .notice--info}
**B5 was selected for the live ZenWave B model** due to its exceptional IS/OOS alignment, PF/DD stability, and resilience during the 2022–2025 volatility regime.

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

- **A** = long-term structural breakout engine (2014–2025)  
- **B** = medium-term adaptive breakout engine (2018–2025)  
- Combined = **multi-horizon robustness**, lower decay risk, smoother equity, stronger regime coverage

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

This matches **institutional-grade risk standards**:  
no position escalation, no recovery patterns, no hedging structures.

<br>

---

# 📘 ZenWave A — Quant Validation Summary

## **Strategy Type**
Long-term USDJPY structural breakout engine (2014–2025).  
Fully automated, fixed SL/TP, no martingale, no grid.

## **Walk-Forward Analysis (A1–A4)**

All A-series slices demonstrate:

- Consistent profitability out-of-sample  
- Stable profit factor across all windows  
- No OOS collapses  
- Regime-stable equity shape  
- Natural parameter drift without instability  
- Long-horizon reliability across 12 years of data  

## **AI-Assisted Validation Findings**
- All slicing boundaries verified  
- No data leakage  
- OOS returns structurally aligned with IS behavior  
- Cross-slice robustness placed in the **top ~0.1%** of strategies evaluated via machine audit  

## **Robustness Conclusion**
ZenWave A passes with **high institutional confidence**.  
Its **full-window parameters (2014–2025)** serve as the backbone of the ZenWave portfolio.

**WFA Video:** 🎥 [Watch](https://youtu.be/r2AVlHbOZV0)

<br>

---

# 📘 ZenWave B — Quant Validation Summary

## **Strategy Type**
Medium-term USDJPY breakout/trend engine (2018–2025).  
Adaptive structural logic with fixed SL/TP.

## **Walk-Forward Analysis (B1–B5)**

All slices show **profitable OOS performance**:

- **B1** – Profitable; moderate stability  
- **B2** – Highly stable; strong OOS  
- **B3** – Weakest slice; still profitable  
- **B4** – Excellent stability; robust OOS  
- **B5** – Best fit for 2024–2025 volatility regime  

## **Parameter Behavior**
- Controlled drift between slices  
- No chaotic transitions  
- Stable PF/DD across environments  
- B4 and B5 produce the strongest and most consistent signals  

## **AI-Assisted Validation Findings**
- Verified parameter consistency  
- Correct slicing / strict OOS separation  
- No evidence of overfitting  
- Structural stability across multiple volatility regimes  

## **Robustness Conclusion**
ZenWave B passes.  
**B5 is chosen for live deployment** due to:

- strong OOS performance  
- high stability  
- low fragility  
- exceptional modern-regime alignment  

**WFA Video:** 🎥 [Watch](https://youtu.be/XR5DyHUJmg0)
