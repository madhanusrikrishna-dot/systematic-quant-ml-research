# Systematic Quant ML Research

A Python-based quantitative research portfolio demonstrating data engineering, feature engineering, regression-based machine learning, walk-forward validation, simulation design, and Monte Carlo robustness testing on intraday financial time-series data.

> This repository is a public portfolio showcase. Core research logic, exact strategy rules, thresholds, and proprietary implementation details are intentionally kept private.

---

## Project Overview

This project demonstrates an end-to-end research workflow for systematic intraday market analysis.

The goal is not to expose a trading signal, but to show the engineering process behind building structured research infrastructure:

- Data preprocessing and validation
- Intraday feature engineering
- Regression-based machine learning workflows
- Walk-forward validation
- Out-of-sample simulation
- Equity curve tracking
- Monte Carlo robustness testing
- Drawdown and distribution analysis

---

## Research Pipeline

```text
Raw Market Data
        ↓
Data Normalization
        ↓
Feature Engineering
        ↓
Model Research
        ↓
Walk-Forward Validation
        ↓
Model Export
        ↓
Out-of-Sample Simulation
        ↓
Monte Carlo Robustness Testing
Key Components
1. Data Engineering

The preprocessing layer focuses on transforming raw intraday OHLCV data into structured research-ready datasets.

It includes:

Market-session filtering
Timestamp validation
Missing-value handling
Rolling statistical calculations
Time-series feature preparation
2. Feature Engineering

The feature engineering layer creates intraday market features based on:

Price movement
Volatility
Volume behavior
Trend structure
VWAP-based relationships
Rolling normalization
3. Machine Learning Workflow

The research process uses regression-based machine learning workflows for predictive modeling and signal evaluation.

The model research layer includes:

Feature-combination testing
Train/validation/test separation
Walk-forward validation
Consistency-based candidate evaluation
Reproducible model artifact creation
4. Simulation Engine

The simulation layer evaluates model behavior on unseen data using a chronological event-driven process.

It tracks:

Equity curve
Trade events
Portfolio-level performance summaries
Monthly summaries
Drawdown behavior
Risk-adjusted metrics
5. Monte Carlo Robustness Testing

Monte Carlo simulation is used to stress-test the distribution of possible outcomes by resampling trade sequences.

It helps analyze:

Final equity distribution
Drawdown distribution
Path dependency
Outcome variability
Robustness under randomized trade ordering
Visual Outputs
Equity Curve

Monte Carlo Equity Curve Simulation
## Key Components

Final Equity Distribution

Drawdown Distribution

Tech Stack
Python
pandas
NumPy
scikit-learn-style regression workflows
Joblib
Numba
Matplotlib
Skills Demonstrated

This project demonstrates practical experience in:

Python development
Data engineering
Feature engineering
Machine learning workflows
Quantitative research
Simulation design
Statistical validation
Automation
Research pipeline architecture
Repository Note

This is a portfolio-level research showcase.

Sensitive implementation details, exact strategy logic, thresholds, execution rules, and proprietary research code are intentionally excluded from the public repository.

The purpose of this repository is to demonstrate research engineering ability, not to publish a complete trading system.

Author

Built independently as part of my quantitative research, machine learning, and Python engineering learning journey.

Focused areas:

Python development
Quantitative research
Machine learning
Data engineering
Automation
AI/LLM workflows
