---
layout: single
title: "Risk Tiers & Baseline Requirements"
permalink: /risk-tiers/
author_profile: true
---

All tiers use the same engine logic; only **risk per trade** and **baseline capital** differ.

---

## 📊 Tier Structure

| Tier | Risk/Trade | A-Series Fee | B-Series Fee | C-Series Fee |
|------|------------|--------------|--------------|--------------|
| **Aggressive** | **1.00%** | 10% | 20% | 25% |
| **Balanced** | **0.75%** | 8% | 15% | 20% |
| **Conservative** | **0.50%** | 6% | 12% | 15% |
| **Ultra-Conservative** | **0.25%** | 4% | 8% | 10% |

---

## 💵 Required Baselines  
Minimum trade size: **0.01 lots**  
To preserve risk accuracy:

| Tier | Baseline Capital |
|------|-------------------|
| **Aggressive (1.00%)** | **$350** |
| **Balanced (0.75%)** | **$470** |
| **Conservative (0.50%)** | **$700** |
| **Ultra-Conservative (0.25%)** | **$1,400** |

---

## 📌 Release Rule  
A risk tier is released once subscription revenue seeds the **baseline capital** needed for accurate %-risk sizing and minimum-lot execution.
