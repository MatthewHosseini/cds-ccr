## Notebooks (Credit, CCR, Rates)

### `scripts/vector_ai.ipynb`
Notebook exploring a **CCR-oriented credit workflow** with an emphasis on a **data / vector-AI** style approach (feature engineering, representations, and downstream analytics). This is the current “active” CCR notebook in the repo. Notes and notebooks for **CDS curve calibration** and **hazard-rate / intensity construction** (and, where relevant, mapping into default probability / intensity matrices for CCR-style simulations) are **planned** and will be added in upcoming commits.

### `scripts/ir_vol_Products.ipynb`
A desk-oriented notebook covering **interest rate volatility products** (caps/floors, swaptions, and a bridge to early-exercise intuition), with emphasis on:
- quote path: curves + surface → forwards/par rates → annuities → PV
- risk in hedgeable coordinates: **key-rate DV01**, **expiry×tenor vega** (with attribution logic), and higher-order sensitivity intuition
- lightweight **VaR/ES proxy** (Base vs Stress) to demonstrate limit-awareness and regime sensitivity (explicit assumptions; not a production risk engine)

