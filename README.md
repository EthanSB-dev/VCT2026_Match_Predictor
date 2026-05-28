# VCT Match Outcome Predictor

## Overview
This project uses 2026 VCT (Valorant Champions Tour) data from the Kickoff and Masters Santiago tournaments to predict professional match outcomes. The dataset consists of 21 CSV files sourced from a [Kaggle VCT dataset](https://www.kaggle.com/datasets/ryanluong1/valorant-champion-tour-2021-2023-data), covering match results, player statistics, agent pick rates/bans, rounds, economy, and map information.

**Dataset at a glance:**
- ~50,000–100,000 total observations across all files
- 20–30 predictors in the main tables
- Numeric variables: ACS, K/D ratio, pick rate
- Categorical variables: map, agent, tournament stage
- Missing data primarily in low-usage agent columns (e.g., Reyna pick rate nulled due to insignificance)

## Research Questions
The primary goal is to **predict match win/loss outcomes** (binary classification: 1 = win, 0 = loss). The project is mainly predictive but includes a descriptive component to identify which in-game statistics are most associated with winning.

**Expected key predictors:** team ACS, K/D ratio, first-kill rate, map, and tournament stage.

## Project Timeline
| Phase | Weeks | Goals |
|---|---|---|
| Data Preparation | Week 3 | Clean, load, and merge all CSV files |
| EDA | Weeks 4–5 | Visualizations, predictor analysis, missing data patterns |
| Modeling | Weeks 6–7 | Build and compare classification models, evaluate and refine |
| Interpretation | Weeks 8+ | Interpret results and finalize conclusions |

