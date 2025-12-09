---
layout: single
title: "ZenWave A — 12-Year Walk-Forward-Validated Architecture"
author_profile: true
---

**AI-accelerated quant research focused on long-horizon Walk-Forward-validated USDJPY engines, strict risk controls, and full automation.**

<img src="/zenwave-a-12-secs.gif" alt="ZenWave A USDJPY equity curve 12 years in 12 seconds" width="700">

<br>

ZenWaveCapital is an **AI-accelerated quantitative research project**—a private, fully anonymous quant lab focused exclusively on **long-horizon USDJPY breakout engines** across three structural timeframes.

The project uses a **dual-AI validation workflow**:
- An internal AI assists in **WFA slicing, statistical auditing, and bias mitigation**,  
- While an external public AI is used as an **independent secondary auditor** to confirm methodological rigor and eliminate hidden assumptions.

This mirrors the **multi-layer validation pipelines** used in modern institutional quant teams.

ZenWave consists of three engines:

- **ZenWave A** – Long-term structural breakout engine (12-year WFA-validated)  
- **ZenWave B** – Medium-term adaptive structural engine (5-slice WFA-validated)  
- **ZenWave C** – Short-term volatility engine (development begins 2026)

All models follow strict institutional principles:

- **Deterministic rule sets** and **server-side execution**  
- **Mandatory SL/TP on every trade**  
- **No martingale, no grid, no hedging stacks**  
- **No leverage escalation during drawdowns**  
- **Multi-slice WFA as the core robustness standard**  
- **AI-assisted validation and external AI governance review**  

[📊 ZenWave Quant Report](/quant-report/){: .btn .btn--primary}

<br>

---

## 🧠 Portfolio Architecture (A/B/C Engines)

            ZenWave Portfolio
                    │
        ┌───────────┼───────────┐
        │           │           │
    ZenWave A   ZenWave B    ZenWave C
    Long-Term   Medium-Term  Short-Term
        │           │           │
        └───────────┴───────────┘
                    │
              Combined Output

This architecture provides **multi-horizon diversification**,  
reducing regime risk and improving long-term stability.

<br>

---

## 🚀 Current Public Strategies

ZenWaveCapital began its **public live performance** on **23.11.2025** with two clean, freshly seeded accounts:

- **ZenWave A — €300 starting balance**  
- **ZenWave B — €300 starting balance**

These accounts form the **official transparent public track record** for ZenWave's USDJPY engines.

🔗 **cTrader Profile:**  
View all public strategies:  
**[ZenWaveCapital on cTrader](https://ctrader.com/u/ZenWaveCapital)**

---

### ⚙️ ZenWave A — Long-Term Structural Breakout Engine (1.0% risk per trade)

**Type:** Long-horizon structural breakout engine  
**Status:** Walk-Forward validated ✔ (A1–A4 slices passed)  
**WFA Video:** 🎥 [Watch on YouTube](https://youtu.be/r2AVlHbOZV0)

ZenWave A is built from a **12-year structural optimization window (2014–2025)**.  
Walk-Forward Analysis across four long-term slices confirmed:

- **Parameter stability**  
- **Consistent OOS performance**  
- **Resilience across volatility regimes**  
- **Long-horizon structural persistence**

The engine uses the **full-window parameter set**, justified by uniform cross-slice behavior.

**Backtest period:** 11Y 9M (19/01/2014 – 14/11/2025)

#### 📊 Key Metrics  
- **Profit Factor:** 2.08  
- **Max Drawdown:** 35.61%

---

### ⚙️ ZenWave B — Medium-Term Adaptive Engine (1.0% risk per trade)

**Type:** Medium-term adaptive structural engine  
**Status:** Walk-Forward validated ✔ (B1–B5 slices passed)  
**WFA Video:** 🎥 [Watch on YouTube](https://youtu.be/XR5DyHUJmg0)

ZenWave B targets medium-horizon drift and structural volatility shifts, validated across  
**five WFA slices (2018–2025)**.

Production parameters come from the **median slice**, selected for:
- High IS/OOS alignment  
- Balanced PF/DD profile  
- Resilience during volatility expansions  
- Stability across multiple structural regimes  

**Backtest period:** 7Y 4M (01/07/2018 – 14/11/2025)

<br>

---

## 👷‍♂️ In Development

### ⚙️ ZenWave C — Short-Term Volatility Engine (development starts 2026)

- **Type:** Short-term volatility engine  
- **Status:** Research begins **2026**  
- **Method:** Full multi-slice WFA (C1) will be applied after architecture design  
- **Purpose:** Capture volatility bursts around Tokyo/London transitions  
- **Availability:** Not yet live  
- **Documentation:** Full build will be **openly documented on YouTube** throughout 2026

<br>

---

## 🧭 Multi-Tier Risk Scaling — Future Roadmap

ZenWaveCapital will introduce **risk-tiered versions** as live data matures.  
Each tier uses the same engine architecture, differing only in **percentage risk per trade** and corresponding **baseline capital requirements**.

### Risk Tiers (Fee Structure)

| Tier | Risk/Trade | A-Series Fee | B-Series Fee | C-Series Fee |
|------|------------|--------------|--------------|--------------|
| **Aggressive** | **1.00%** | 10% | 20% | 25% |
| **Balanced** | **0.75%** | 8% | 15% | 20% |
| **Conservative** | **0.50%** | 6% | 12% | 15% |
| **Ultra-Conservative** | **0.25%** | 4% | 8% | 10% |

### Baseline Capital Requirements  
To maintain accurate percentage risk and minimum **0.01 lot** position sizing, each tier requires a different verification baseline:

| Tier | Baseline Required |
|------|--------------------|
| **Aggressive (1.00%)** | **$350** |
| **Balanced (0.75%)** | **$470** |
| **Conservative (0.50%)** | **$700** |
| **Ultra-Conservative (0.25%)** | **$1,400** |

### Release Rule  
A risk tier becomes available once subscription revenue seeds the **appropriate baseline verification account** for that tier.  
Lower-risk tiers require **higher baseline capital** to preserve risk accuracy and avoid position-size distortion.

<br>

---

## 📊 Philosophy & Principles

- Single-instrument specialization: **USDJPY only**  
- Real tick data, realistic spreads  
- Pending orders only  
- Mandatory SL/TP on every trade  
- **No martingale / no grid / no hedge stacking**  
- **No optimization tricks**  
- Multi-slice WFA as core robustness  
- Multi-horizon diversification  
- **AI-assisted statistical auditing + external AI governance**

<br>

### 🔐 Risk-Control Framework

    Position Sizing (1% risk)
           │
           ▼
     Stop-Loss Logic
           │
           ▼
     Take-Profit Logic
           │
           ▼
    ┌───────────────────────────────────┐
    │  No Martingale                    │
    │  No Grid                          │
    │  No Simultaneous Hedge Positions  │
    └───────────────────────────────────┘
           │
           ▼
     Server-Side Execution

<br>

---

## 🕶️ Anonymity by Design

ZenWaveCapital is **intentionally anonymous**.  
This keeps the focus on **methodology**, **quant engineering**, and **validation standards**, rather than on personal identity or background.

This approach mirrors common practices in:

- private quant research labs  
- prop trading groups  
- algorithmic development teams  
- high-assurance engineering projects  

Anonymity protects both the intellectual property and the independence of the research.

<br>

---

## 📜 Disclaimer

Trading FX and CFDs on margin involves a **high level of risk** and may not be suitable for all investors.  
You may lose more than your initial investment.

- Past performance does not guarantee future results  
- Nothing here constitutes investment or financial advice  
- This material is for educational purposes only
