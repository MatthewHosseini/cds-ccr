# Quant Notebooks (Rates, Credit, CCR)

This repository contains working notes and notebooks for pricing, calibration, and risk workflows used in front-office / XVA / CCR contexts. The emphasis is on **transparent assumptions**, **reproducible calculations**, and **desk-style risk decomposition** where applicable.

---

## Interest Rate Volatility (IR Vol)

### `IR_Volatility_Products.ipynb`
A desk-oriented notebook covering **IR volatility products** (caps/floors, swaptions, and a bridge to early-exercise intuition), with emphasis on:
- quote path: curves + surface → forwards/par rates → annuities → PV
- risk in hedgeable coordinates: **key-rate DV01**, **expiry×tenor vega** (with attribution logic), and higher-order sensitivity intuition
- lightweight **VaR/ES proxy** (Base vs Stress) to demonstrate limit-awareness and regime sensitivity (explicit assumptions; not a production risk engine)

---

## Credit / CCR (CDS → Intensities)

A couple of documents about how to **calibrate CDS curves** and then use them to generate **intensity (hazard) matrices**, primarily for **CCR analysis**.

---

## Notes
- These materials are educational and workflow-oriented; they are not a substitute for production pricing/risk libraries.
- Any VaR/ES content is intentionally lightweight and assumption-driven to illustrate concepts and attribution.
