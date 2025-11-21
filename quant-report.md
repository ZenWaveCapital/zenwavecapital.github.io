---
layout: default
title: ZenWave A + B Quantitative Validation Report
---

# ZenWaveCapital Quantitative Validation Report  
**Models:** ZenWave A & ZenWave B  
**Market:** USDJPY  
**Methodology:** Systematic, Quantitative, Fully Automated

---

## 📘 ZenWave A — Quant Validation Summary

### **Strategy Type**
Long-term quantitative breakout engine for USDJPY (2014–2025).  
Fixed SL/TP, fully rule-based, no martingale, no grid.

### **Walk-Forward Analysis (A1–A4)**
- All slices profitable out-of-sample.  
- Profit factor stable across slices.  
- Drawdowns remained controlled in OOS (no blow-ups).  
- Equity curves across slices look very similar.  
- Parameters naturally stable across a decade of different market regimes.

### **Robustness Conclusion**
ZenWave A passes WFA with **high confidence**.  
The full-window (2014–2025) optimized parameter set demonstrates broad regime robustness and serves as the long-term structural backbone of the ZenWave portfolio.

---

## 📘 ZenWave B — Quant Validation Summary

### **Strategy Type**
Medium-term quantitative breakout/trend engine for USDJPY (2018–2025).  
Modern volatility model, adaptive breakout logic, fixed SL/TP.

### **Walk-Forward Slices (B1–B5)**  
All slices produced **profitable out-of-sample performance**:

- **B1** – Profitable; moderate stability; early regime.  
- **B2** – Strong OOS performance; high stability.  
- **B3** – Weakest slice; still profitable (no failure).  
- **B4** – Excellent OOS performance; very high stability.  
- **B5** – Excellent OOS performance; very high stability; best match for the 2024–2025 volatility regime.

### **Parameter Behavior**
- Controlled drift between slices (expected for medium-term adaptive systems).  
- No chaotic or fragile parameter shifts.  
- OOS behavior remains consistent regardless of drift.  
- B4 and B5 show the strongest stability and regime fit.

### **Robustness Conclusion**
ZenWave B passes WFA.  
The **B5 parameter set** is recommended for live production based on:
- strong OOS performance,  
- controlled drawdowns,  
- stability, and  
- best alignment with current USDJPY conditions.
