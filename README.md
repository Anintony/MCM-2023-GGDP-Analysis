# MCM 2023: GGDP vs. GDP (Problem F)

This repository contains the final paper for our team's (2300870) submission to the 2023 Mathematical Contest in Modeling (MCM).

**Problem:** "Together for a Green World" - Analyzing the global impact of adopting Green GDP (GGDP) as an alternative to traditional GDP.

---
### **Award: Honorable Mention (H Award)**
*Our paper was recognized with an Honorable Mention, placing it in the top tier of international submissions.*
---

**Final Paper:** [`2300870.pdf`](./2300870.pdf)
---

## Methodology

Our analysis involved a multi-step modeling process to compare the long-term environmental impacts of both economic models:

1.  **Forecasting:** We used time series models (including **ARIMA** and **Holt's Linear Trend**) to forecast future traditional GDP growth.
2.  **Climate Index:** We constructed a composite "Climate Quality Index" (CQI) by weighting four key indicators (Total Greenhouse Gas, Avg. Temperature, Avg. Precipitation, Forest Area).
3.  **Weighting:** The weights for the index were objectively determined using the **Entropy Weight Method (EWM)**.
4.  **Impact Analysis:** We ran two separate regression models to compare the long-term impact of a GDP-based economy vs. a GGDP-based economy on our Climate Quality Index.

## Key Finding

Our models demonstrated that a global development strategy focused on **GGDP leads to significantly better long-term environmental outcomes** and sustainability compared to one focused on traditional GDP.
