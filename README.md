# Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

Many small‑scale farmers can’t afford to run a full lab panel on their soil every season.  
This project shows how **simple machine‑learning models** can highlight which *single* soil metric delivers the most bang for the buck when predicting the best crop to plant.

---

## Problem Statement

A farmer supplied a dataset (`soil_measures.csv`) containing four soil metrics and the *ideal* crop label for each sample:

| Column | Description |
|--------|-------------|
| `N`    | Nitrogen ratio |
| `P`    | Phosphorous ratio |
| `K`    | Potassium ratio |
| `ph`   | Soil pH value |
| `crop` | Target crop *(22 categories)* |

> **Goal:** Build one‑feature logistic‑regression models and determine which metric (N, P, K, or pH) alone gives the highest predictive power.
