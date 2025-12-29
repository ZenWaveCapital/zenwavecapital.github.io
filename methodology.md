---
layout: single
title: "Methodology — How ZenWave Works"
permalink: /methodology/
author_profile: true
---

AI-Accelerated · Multi-Slice Walk-Forward · Fully Automated

ZenWave Capital is built as a **systematic research lab**, not a discretionary trading project.  
All engines follow the same methodological spine: strict validation, bounded risk, and non-negotiable automation.

---

## 🧠 AI-Accelerated Research Workflow

ZenWave operates under **dual AI governance**, separating *generation* from *verification*.

### Internal AI (Research & Construction)
Used for:
- Hypothesis testing
- Walk-Forward slice construction
- Parameter sensitivity analysis
- Leakage detection
- Robustness and stress testing

Internal AI is constrained, deterministic, and auditable.

### External AI (Independent Oversight)
Used for:
- Methodology review
- Bias and overfitting detection
- Architecture sanity checks
- Failure-mode analysis

This separation mirrors institutional practices where **model creation and model approval are never owned by the same process**.

---

## 📐 Walk-Forward Analysis (WFA)

All ZenWave engines are validated using **multi-slice Walk-Forward Analysis**, not single in-sample optimizations.

Each engine undergoes:
- Independent IS / OOS partitions
- Multiple chronological slices
- No parameter reuse across slices
- Strict anti-leakage boundaries
- Regime-aware validation
- Profit factor and drawdown stability checks
- Parameter drift assessment

A system is considered valid **only if it demonstrates stability across slices**, not peak performance in any one period.

Optimization-for-marketing is explicitly rejected.

---

## 🌐 Research Focus: Why USDJPY

ZenWave research is **intentionally limited to a single market**: USDJPY.

This is a design decision, not a constraint.

USDJPY offers:
- Deep, continuous liquidity
- Tight spreads across regimes
- Long, uninterrupted historical data
- Distinct structural and macro regimes
- Clean execution characteristics for automation

By fixing the market, ZenWave reduces degrees of freedom and avoids curve-fitting across instruments.  
All complexity is allocated to **structure, regime behavior, and execution quality** — not symbol selection.

---

## 🔐 Institutional Risk Controls

Every engine adheres to the same hard constraints:

- No martingale
- No grid logic
- No hedge stacking
- Mandatory stop-loss and take-profit
- Server-side execution only
- Deterministic, rule-based logic
- No discretionary overrides
- No manual trade intervention

Risk is defined **before** execution and enforced mechanically.

If a system cannot survive strict risk constraints, it is discarded.

---

## 🧩 Portfolio Architecture

ZenWave is structured as a **multi-horizon system portfolio**, not a single strategy.

- **ZenWave A** — Long-term structural engine  
  Designed to capture regime expansions and convex moves.

- **ZenWave B** — Medium-term adaptive engine  
  Designed to operate across mixed and transitional regimes.

- **ZenWave C** — Short-term volatility engine *(2026)*  
  Designed for intraday compression and expansion cycles.

Each engine is independent, risk-bounded, and non-correlated by design.

Together, they form a portfolio architecture focused on **robustness over regimes**, not smooth equity curves.

---

## 📊 Validation Philosophy

ZenWave systems are judged by:
- Survivability
- Stability across time
- Behavioral consistency
- Failure containment

Not by:
- Peak returns
- Short-term equity smoothness
- Backtest aesthetics

Drawdowns are treated as **structural costs**, not defects.

---

<small>
ZenWave Capital is an independent quantitative research project.  
No signal selling. No discretionary trading. No optimization for presentation.
</small>
