# RWA Impact Analysis: Basel III vs. Basel III Endgame Proposal (American Express)

## Overview
This project evaluates the impact of the **Basel III Endgame (NPR)** on **Risk-Weighted Assets (RWA)** and capital ratios for **American Express**, using publicly disclosed regulatory and financial data.

The analysis focuses on **Credit Risk, Counterparty Credit Risk (CCR), Credit Valuation Adjustment (CVA), and Operational Risk**, and explicitly reflects **American Express’s business model**, which does **not include trading activities or market risk exposure**.

All results and impacts are derived from the accompanying presentation and regulatory disclosures. 

---

## Data Sources
The analysis is based on the following disclosures:
- **American Express 10-K / 10-Q** – balance sheet composition and business model context  
- **FR Y-9C** – baseline RWAs, CET1, Tier 1, and Total Capital ratios  
- **FR Y-15** – systemic risk indicators and capital relevance  

> **Note:** American Express does **not** file FFIEC 101, as it has **no exposure subject to Market Risk Rules**. This is confirmed by FR Y-9C filings showing zero trading assets and liabilities. :contentReference[oaicite:1]{index=1}

---

## Scope and Key Assumptions

- **Market Risk RWA:** **0**
  - No trading book
  - No correlation trading
  - Only minimal hedging derivatives (not trading)
  - Therefore, **Market Risk Rule does not apply**

- **SFT Exposure:** **0**
  - No repo or securities lending activity
  - No prime brokerage
  - No securitization exposures

These exclusions materially shape the Basel III Endgame impact for American Express. :contentReference[oaicite:2]{index=2}

---

## Basel III Baseline Snapshot

- **CET1 Capital:** \$26,222 million  
- **Risk-Weighted Assets (RWA):**
  - Standardized Approach (SA): **\$250,642 million**
  - ERBA-adjusted: **\$209,770 million**

- **CET1 Ratios:**
  - SA: **10.46%**
  - ERBA: **12.13%**

Baseline RWAs include:
- General Credit Risk
- Counterparty Credit Risk
- Credit Valuation Adjustment (CVA)
- Operational Risk  
(No Market Risk component)

:contentReference[oaicite:3]{index=3}

---

## Credit Risk Impact (Basel III Endgame)

### General Credit Risk
Under the Endgame proposal:
- Risk weights become more granular (corporates, retail sub-segments)
- Retail exposures move from flat 100% RW to:
  - Transactor retail (55%)
  - Regulatory retail (85%)
  - Other retail (100%)

### Off-Balance Sheet Exposures
- **Credit Conversion Factors (CCF)** change:
  - Unused commitments: **0.5 → 0.4**
  - Unconditionally cancellable commitments: **0 → 0.1**

This is significant given American Express’s large unused commitment base.

:contentReference[oaicite:4]{index=4}

---

## Counterparty Credit Risk (CCR) & CVA Impact

- **Basel III CCR RWA:** \$95.46 million  
- **Basel III Endgame CCR RWA:** \$96.60 million  
  - Derived using ERBA scaling (≈0.97%)

- **CVA RWA under Basel III Endgame:**  
  - Assumed ≈ **30% of CCR RWA**
  - **CVA RWA:** \$27.78 million

> Under Basel III, CVA RWA = 0  
> Under Basel III Endgame, CVA becomes binding

:contentReference[oaicite:5]{index=5}

---

## Operational Risk Impact (SMA)

Operational Risk is calculated using the **Standardized Measurement Approach (SMA)**.

- **Business Indicator (BI):** \$12,580,162  
- **Business Indicator Component (BIC):** \$1,857,024  
- **Internal Loss Multiplier (ILM):** 1.00 (no internal loss data)

### Final Operational Risk RWA
Operational Risk Capital = BIC × ILM
RWA = Capital × 12.5
Final Operational RWA = $23,212,803

Operational Risk contributes **~9.14% of total RWA impact**, making it one of the most material drivers under Basel III Endgame.

:contentReference[oaicite:6]{index=6}

---

## AOCI Opt-Out Impact on Capital Ratios

- AOCI loss of **–\$3.249B** is excluded from CET1 under the Endgame opt-out
- CET1, Tier 1, and Total Capital all increase mechanically

### Capital Ratio Improvements
- **CET1 Ratio:** 10.46% → **11.76%**
- **Tier 1 Ratio:** 11.11% → **12.41%**
- **Total Capital Ratio:** 13.07% → **14.37%**

This improvement occurs **without any balance sheet change**, purely from regulatory treatment.

:contentReference[oaicite:7]{index=7}

---

## Sensitivity Analysis (Basel III Endgame)

- **Total RWA Change:** **–\$40,997.71 million (–16.14%)**
- **CET1 Ratio Sensitivity (10% RWA increase):** **–1.29%**

Key contributors:
- Loans & leases: **–25.42%**
- Operational Risk: **+9.14%**
- CVA: marginal but non-zero
- Unconditionally cancellable commitments: **+1.55%**

:contentReference[oaicite:8]{index=8}

---

## Key Takeaways

- Basel III Endgame meaningfully reshapes RWAs for American Express **without market risk exposure**
- **Operational Risk and CVA** emerge as new capital drivers
- **AOCI opt-out materially stabilizes CET1**
- Business model (non-trading, non-dealer) significantly limits downside risk relative to universal banks

---

## Strategic Implications
Potential actions highlighted by the analysis:
- Optimize unused commitment management
- Strengthen operational risk controls to reduce SMA capital
- Maintain AOCI opt-out to limit capital volatility
- Use derivatives strictly for hedging, not trading

:contentReference[oaicite:9]{index=9}

---

## References
- Basel III Endgame (NPR)
- American Express FR Y-9C
- American Express FR Y-15
- American Express Pillar 3 Disclosures
