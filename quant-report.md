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

#### **A-Series WFA Timeline**

    A-Series (2014–2025)

    ┌───────────┬───────────┬───────────┬───────────┬───────────┬───────────┬───────────┬───────────┐
    │   A1 IS   │  A1 OOS   │   A2 IS   │  A2 OOS   │   A3 IS   │  A3 OOS   │   A4 IS   │  A4 OOS   │
    │ 2014–2018 │ 2019–2020 │ 2016–2020 │ 2021–2022 │ 2018–2022 │ 2023-2024 │ 2019-2023 │ 2024-2025 │
    └───────────┴───────────┴───────────┴───────────┴───────────┴───────────┴───────────┴───────────┘

#### **B-Series WFA Timeline**

    B-Series (2018–2025)

    ┌───────────┬───────────┬───────────┬───────────┬────────────┐
    │   B1 IS   │  B1 OOS   │   B2 IS   │  B2 OOS   │    B3–B5   │
    │ 2018–2020 │ 2020–2021 │ 2021–2023 │ 2023–2024 │ 2024–2025  │
    └───────────┴───────────┴───────────┴───────────┴────────────┘

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
