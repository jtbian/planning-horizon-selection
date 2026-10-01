# Planning Horizon Selection in Regularized Portfolio Optimization

Academic research on selecting the planning horizon in multi-period portfolio optimization.

## Overview

This project studies whether selecting a planning horizon can improve portfolio decisions under noisy financial estimates. It extends mean-variance optimization across multiple historical estimation segments and uses an L1 penalty on changes between adjacent portfolio weights to regularize allocation changes.

A Python-based monthly walk-forward evaluation compares fixed-horizon strategies with a validation-based adaptive-horizon approach. The analysis examines portfolio return, risk, Sharpe ratio, maximum drawdown, and turnover, with robustness checks across shifted backtests, asset-universe sizes, covariance estimators, and regularization settings.

## Findings and limitations

The adaptive-horizon approach does not consistently outperform fixed-horizon or benchmark strategies. The research highlights the risk of selection noise when validation signals are weak. Results are for academic analysis and are not investment advice.

## Repository status

This repository currently documents the research project. The original research notebooks and data are not included; they are being reviewed and cleaned before any public release.
