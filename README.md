# EcoMobility5442
# COM7021 Data Visualisation: EcoMove City Transport Authority

- **Student ID:** 24205517
- **Module:** Data Visualisation (COM7021)
- **Dataset:** `EcoMoveMobility.xlsx` (5,000 route-level records, Jan 2024 – Dec 2025)

## Overview
This repository contains the data preparation scripts, statistical tests, static visualisations, interactive Plotly charts, and the Plotly Dash analytical dashboard developed to investigate urban mobility performance across 12 European cities and 6 transport modes.

## Repository Structure
- `notebooks/COM7021_EcoMove_24205517.ipynb` — Complete Google Colab notebook
- `eco_analysis.py` — Data cleaning, validation checks, and static Matplotlib/Seaborn visualisations (Figures 1–8)
- `stats_tests.py` — Hypothesis tests, OLS regressions, and bootstrap confidence intervals
- `dashboard.py` — Interactive Plotly Dash application (Figures 9–11)
- `interactive_charts.py` — Standalone interactive Plotly versions of Figures 1–8
- `requirements.txt` — Python package dependencies

## Quick Start (Local Execution)
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Place `_5442__EcoMoveMobilityDV.xlsx` in the project root directory.
3. Run the static analysis and statistical tests:
   ```bash
   python eco_analysis.py
   python stats_tests.py
   ```
4. Launch the interactive dashboard:
   ```bash
   python dashboard.py
   ```
