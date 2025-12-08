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
**Methodology:** Systematic, Quantitative, Fully Automated

---

### 📐 Walk-Forward Analysis (WFA) Overview

ZenWave uses **multi-slice Walk-Forward Analysis (WFA)** to validate robustness across independent out-of-sample (OOS) windows.  
All slices for both A and B show profitable, stable performance across distinct market regimes.

#### A-Series WFA Timeline

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
*A4 uses an extended IS window purely for validation.  
Live A uses the full-window 2014–2025 parameter set, validated by all A1–A4 OOS slices.*

#### B-Series WFA Timeline

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
**The B5 parameter set was selected for the live B engine** because it showed the strongest alignment between IS and OOS performance,  
the most stable PF/DD behavior across 2022–2025, and the highest robustness during the latest volatility regime.

<br>

---

### 🧠 Portfolio Structure (A/B Engines)

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

- **A** = structural, long-term engine (2014–2025)
- **B** = modern-regime, medium-term breakout engine (2018–2025)
- Combined: complementary horizons → smoother equity and lower decay risk

---

### 🔐 Risk-Control Framework (A & B)

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

This matches institutional-grade risk standards: no position escalation, no grid layers, and no offset-hedge structures.

<br>

---

<br>

## 📘 ZenWave A — Quant Validation Summary

### **Strategy Type**
Long-term USDJPY breakout engine (2014–2025).  
Fixed SL/TP, rule-based automation, no martingale, no grid, no simultaneous hedging.

#### **Walk-Forward Analysis (A1–A4)**
- All slices profitable out-of-sample  
- Stable profit factor across windows  
- Controlled drawdowns, no OOS failures  
- Consistent equity shape across market regimes  
- Parameters show natural stability across a decade  

#### **Robustness Conclusion**
ZenWave A passes WFA with **high confidence**.  
The full-window (2014–2025) parameter set is validated and serves as the portfolio’s long-horizon backbone.

- **WFA Video:** 🎥 [Watch on YouTube](https://youtu.be/r2AVlHbOZV0)

<br>

---

<br>

## 📘 ZenWave B — Quant Validation Summary

#### **Strategy Type**
Medium-term USDJPY breakout/trend engine (2018–2025).  
Adaptive breakout logic with fixed SL/TP.

#### **Walk-Forward Analysis (B1–B5)**
All slices produced **profitable** out-of-sample performance:

- **B1** – Profitable; moderate stability  
- **B2** – Strong OOS; high stability  
- **B3** – Weakest slice; still profitable  
- **B4** – Excellent stability; strong OOS  
- **B5** – Best alignment with 2024–2025 volatility regime  

#### **Parameter Behavior**
- Expected, controlled drift between slices  
- No chaotic or fragile behavior  
- OOS performance robust across changing volatility regimes  
- B4 and B5 slices indicate strongest stability and regime-fit

#### **Robustness Conclusion**
ZenWave B passes WFA.  
B5 parameter set is recommended for live use, offering:
- strong OOS behavior  
- controlled drawdowns  
- parameter stability  
- high regime alignment

- **WFA Video:** 🎥 [Watch on YouTube](https://youtu.be/XR5DyHUJmg0)
