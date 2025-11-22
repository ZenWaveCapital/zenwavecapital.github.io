## 📌 Overview

ZenWaveCapital focuses exclusively on **USDJPY breakout engines** across three time horizons:

- **ZenWave A** – Long-term USDJPY breakout engine  
- **ZenWave B** – Medium-term USDJPY trend & breakout engine  
- **ZenWave C** – Short-term, high-adaptation USDJPY breakout engine  

All models:

- Use **fixed rules** and **server-side execution**  
- Run with **strict SL/TP**, **no martingale**, **no grid**, and **no simultaneous hedge positions**  
- Are developed with **Walk-Forward Analysis (WFA)** and robustness as core design principles

<br>
<br>

## 🧠 Portfolio Architecture (A/B/C Engines)

             ZenWave Portfolio
                    │
        ┌───────────┼───────────┐
        │           │           │
    ZenWave A    ZenWave B   ZenWave C
    Long-Term    Medium-Term Short-Term
        │           │           │
        └───────────┴───────────┘
                    │
             Combined Output

This structure creates **multi-horizon diversification**, reducing regime risk and improving long-term stability.

---

### 📈 Equity curve from ZenWave A 12-year backtest

<img src="https://iili.io/fdj3Hs1.md.jpg" alt="ZenWave A USDJPY equity curve" width="700">

<br>
<br>

## 🚀 Current Public Strategies

### ⚙️ [ZenWave A (Aggressive, 1.0% risk per trade)](https://ct-sc.icmarkets.com/copy/strategy/108885)
- **Type:** Long-term structural breakout engine  
- **Status:** Walk-Forward validated ✅ (A1–A4 passed)
- **Params used:** Production parameters were selected from a full
  12-year optimization (2014–2025). Walk-forward
  validation (A1–A4) confirmed parameter stability
  and regime robustness, allowing use of the full-
  window parameter set for the live model.
- **Backtest and optimization period:** 11Y 9M (19/01/2014 – 14/11/2025)
- **Next review and re-optimization:** 01/01/2027 📅

#### 📊 Backtest stats
- **Profit Factor (PF):** 2.08  
- **Max Balance DD:** 35.61%

#### 📊 Quant report
[Quant Report](quant-report)

---

### ⚙️ [ZenWave B (Aggressive, 1.0% risk per trade)](https://ct-sc.icmarkets.com/copy/strategy/108888)
- **Type:** Medium-term adaptive trend engine  
- **Status:** Walk-Forward validated ✅ (B1–B5 passed)
- **Params used:** Production parameters are taken from the median
  walk-forward slice, selected for robust IS/OOS
  alignment, PF/DD stability, and resilience across
  2018–2025 volatility regimes.
- **Backtest and optimization period:** 7Y 4M (01/07/2018 – 14/11/2025)
- **Next review and re-optimization:** 01/01/2026 📅

#### 📊 Quant report
[Quant Report](quant-report)

<br>
<br>

## 👷‍♂️ Currently in the Works

### ⚙️ ZenWave C (Aggressive, 1.0% risk per trade)
- **Type:** Short-term modern volatility engine  
- **Status:** ZenWave C is currently in active quantitative research and undergoing a full Walk-Forward Analysis (WFA) across the 2022–2025 USDJPY regime. C will only be released once the complete WFA cycle (C1–C5) is passed and robustness is confirmed across all out-of-sample periods.
- **Purpose:** ZenWave C is designed to capture short-term volatility bursts during Tokyo and London session transitions, complementing the structural long-term engine (A) and the medium-term modern regime engine (B).
- **Availability:** ZenWave C is *not yet available* for copy-trading. Only A and B are currently production-ready.
- **Next update:** Projected after completion of additional WFA slices and parameter stability validation.

<br>
<br>

## 🧭 Future Roadmap: Multi-Tier Risk Scaling

ZenWaveCapital will gradually introduce **lower-risk variants** of each strategy as live performance matures.  
This allows followers to choose a risk level that matches their goals.

### Planned Risk Tiers:

| Tier | Risk/Trade | A-Series Fee | B-Series Fee | C-Series Fee |
|------|-------------|---------------|---------------|---------------|
| **Aggressive** | **1.00%** | 10% | 20% | 25% |
| **Balanced** | **0.75%** | 8% | 15% | 20% |
| **Conservative** | **0.50%** | 6% | 12% | 15% |
| **Ultra-Conservative** | **0.25%** | 4% | 8% | 10% |

### Planned release schedule:
Each additional tier (Balanced, Conservative, Ultra-Conservative)
will be launched once sufficient subscription revenue is available
to seed the required starting balance (approx. €100 per tier).
This ensures that every tier begins with real capital and verified
live performance.

<br>
<br>

## 📊 Philosophy & Principles

- Single-instrument focus: **USDJPY only**  
- Real tick data with realistic spreads  
- Server-side pending orders  
- Strict SL/TP on every trade  
- **No martingale**  
- **No grid**  
- **No simultaneous hedge positions**  
- WFA methodology for robustness  
- Multi-horizon diversification (A/B/C engines)

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
    ┌──────────────────────────────────────────┐
    │  No Martingale                           │
    │  No Grid                                 │
    │  No Simultaneous Hedge Positions         │
    └──────────────────────────────────────────┘
           │
           ▼
     Server-Side Execution

<br>
<br>

## 📢 Updates

Stay informed with official strategy updates, releases, and announcements.  
[Join the Telegram Channel](https://t.me/ZenWaveCapital)

<br>
<br>

## 📜 Disclaimer

Trading FX and CFDs on margin involves a **high level of risk** and may not be suitable for all investors.  
You can lose more than your initial investment.

- Past performance does **not** guarantee future results  
- Nothing on this page constitutes investment or financial advice  
- This information is for **educational and informational purposes only**
