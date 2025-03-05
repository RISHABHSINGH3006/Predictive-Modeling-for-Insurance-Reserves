# Predictive Modeling for Insurance Reserves

## Project Overview
This project focuses on predictive modeling for insurance reserves, specifically for a mutual insurance association covering waste incinerator (WIS) and landfill (non-WIS) sites. The goal is to estimate aggregate claims, expected costs, and Value at Risk (VaR) using statistical methods.

## Objectives
- Estimate equalization reserves using predictive modeling.
- Fit statistical distributions to claims frequency and severity.
- Compute expected annual aggregate claim costs.
- Determine the 80% Value at Risk (VaR) for reserves.
- Assess the impact of increased claim frequency.
- Suggest model improvements and alternative approaches.

## Data & Assumptions
- **Historical Claims Data:** 2016-2020 claims data for 4 WIS and 2 non-WIS sites.
- **Claims Inflation:** All claims are adjusted for 3% annual inflation to 2021.
- **Claims Frequency Model:** Poisson distribution assumed.
- **Claims Severity Model:** Pareto distribution with a shape parameter of 1.5.
- **Expected Aggregate Loss Calculation:** E[S] = E[N] * E[X].
- **VaR Calculation:** Uses the standard normal quantile (0.84) to estimate the 80% threshold.

## Implementation
The PowerPoint presentation (`Predictive_Modeling_Insurance.pptx`) includes:
- **Overview of the insurance problem and predictive modeling approach.**
- **Mathematical modeling of claims frequency and severity.**
- **Computations for expected losses and risk measures.**
- **Evaluation of model performance and suggestions for improvements.**

## Required Software & Tools
- Microsoft PowerPoint or equivalent presentation software.
- R/Python (if further statistical analysis is required).

## Future Enhancements
- Incorporate alternative severity distributions (e.g., lognormal, gamma).
- Introduce Bayesian estimation techniques.
- Apply Machine Learning for anomaly detection and predictive modeling.
- Validate model assumptions using statistical goodness-of-fit tests.

## How to Use
1. Open `Predictive_Modeling_Insurance.pptx` to view the presentation.
2. Review the methodology and results.
3. Adapt the models based on new data or improved assumptions.
