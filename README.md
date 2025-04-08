# Agency Problem and Natural Experiment – Corporate Finance Analysis

This project investigates the agency problem in corporate finance by analyzing the effects of a natural experiment on firm governance behavior. Developed for a graduate-level Topics in Corporate Finance course at HEC Montréal, the notebook replicates and extends empirical findings from the academic literature using panel data regression.

## 📘 Overview

This analysis explores whether changes in external conditions—such as regulatory or policy shocks—affect corporate decision-making and managerial behavior, particularly in the context of the **agency problem**. Using firm-level panel data, the project constructs treatment and control groups to estimate the causal impact of the natural experiment on variables such as:

- CEO duality (CEO also serving as board chair)
- Board independence
- Firm leverage, size, and financial performance

The workflow includes:

- Reading and cleaning annual financial data
- Constructing key governance indicators
- Winsorizing and transforming relevant variables
- Running **fixed-effects panel regressions** with `PanelOLS` to account for unobserved heterogeneity
- Interpreting coefficients within the framework of agency theory

This project demonstrates how **natural experiments** and **econometric techniques** can be applied to corporate finance to test theoretical predictions and uncover real-world implications.

## 📄 Reference

This notebook draws from the findings in the uploaded reference paper:  
**[Reference_Paper.pdf]** – please consult it for theoretical background and identification strategy.

## 🔧 Technologies

- Python
- pandas, NumPy
- statsmodels, scipy
- linearmodels.panel (PanelOLS)
