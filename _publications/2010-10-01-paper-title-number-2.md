---
title: "Optimization Modeling in Finance"
collection: Optimization
category: manuscripts
date: 2024-08-08
paperurl: 'http://Henrychen0624.github.io/files/Machine_Learning_Proj.ipynb'
citation: 'Google'
---

In this project, we explore extensions to the classical Markowitz mean-variance portfolio optimization framework by incorporating practical constraints and regularization techniques. The paper is divided into two parts, where in first part we focus on modifying the optimization function, while in the second part, we add several optimization constraints on the original Markowitz portfolio constraints. Using ETF sector data from 2020, we first implement the traditional Markowitz model, and then progressively apply L1 regularization (LASSO), elastic net penalties, and trading and weight constraints to reflect more realistic trading environments. Furthermore, we introduce a bi-level optimization framework to fine-tune portfolio holding and cash bounds, aiming to find the optimal weight boundaries. We also added return and risk forecasts to protect out model against extreme market volatility circumstances. A 3-month rolling window backtesting procedure is used to assess the out-of-sample performance. The results demonstrate that incorporating realistic trading frictions and promoting portfolio sparsity through regularization can improve the robustness and feasibility of optimized portfolios.
