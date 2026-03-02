# EOLA Fairness Toolkit

The Equity-Oriented Learning Analytics (EOLA) Fairness Toolkit is a reproducible Python implementation accompanying the manuscript:
A Reproducible Fairness-Aware and Explainable Learning Analytics Architecture for Multi-Objective Early Warning Systems in Online Higher Education.

This repository operationalizes the methodological components described in the paper and provides a synthetic proof-of-concept for fairness-aware and explainable Early Warning Systems (EWS).

## Purpose

The EOLA Toolkit demonstrates how predictive performance, subgroup fairness auditing, and explainability diagnostics can be integrated into a unified, governance-aligned Learning Analytics pipeline.

The implementation serves as a reproducible methodological validation of the EOLA architecture and is not based on real institutional data.

## Implemented Components

### Predictive Modeling Layer
- Random Forest classifier (scikit-learn)
- Explicit hyperparameter configuration
- Deterministic training (fixed random seeds)
- Threshold-based binary classification

### Fairness Auditing Layer
- Subgroup performance disparity evaluation
- Equal Opportunity Difference (Δ_EOpp) as primary trade-off metric

### Explainability Layer
- SHAP (TreeExplainer)
- Global feature attribution visualization
- Instance-level explanation capability

### Accuracy–Fairness Trade-off
- AUC vs Δ_EOpp evaluation
- Pareto frontier visualization
- Governance-aligned selection under constraint Δ(θ) ≤ τ

## Synthetic Proof-of-Concept

The toolkit uses a synthetic dataset simulating:
- Academic engagement features
- Performance signals
- A subgroup attribute
- Controlled structural disparity

The synthetic environment is used strictly for methodological validation.

## Reproducibility

- Fixed random seeds
- Script-based figure generation
- Deterministic metric computation
- Structured output logging

All figures in the manuscript can be reproduced using the provided notebook.

## Repository Structure

- README.md
- LICENSE
- CITATION.cff
- requirements.txt
- EOLA_Fairness_Toolkit.ipynb

## License

MIT License

EOLA reframes Early Warning Systems from performance-centered analytics toward reproducible, fairness-aware, and governance-aligned AI infrastructures for higher education.
