# Migration Intelligence Analysis – UIDAI Hackathon 2026

## Project Overview
This project detects **high-velocity internal migration signals** by analyzing Aadhaar enrolment anomalies.
The core idea is to identify districts where enrolment activity jumps suddenly from near-zero to unusually high volumes,
indicating **new settlements or sudden population inflow**.

## Why This Matters
Sudden migration spikes can strain local governance systems such as:
- Healthcare and welfare delivery
- Housing and urban infrastructure
- Employment and public services

Early detection allows policymakers to **shift from reactive to proactive governance**.

## Key Findings
- **Top Hotspot:** Murshidabad, West Bengal  
  → 13,877 new Aadhaar enrolments detected in September 2025.
- **Observed Pattern:**  
  - Border districts of West Bengal show repeated high-velocity spikes  
  - Industrial regions in Gujarat exhibit sustained migration inflows

## Methodology (Signal Logic)
- Aggregated Aadhaar enrolment data analyzed at the district level
- High Velocity Signal defined as:
  - Transition from zero or negligible enrolment
  - To sudden large-scale monthly enrolment activity
- Such transitions are flagged as potential migration events

## Notebook Flow
- `00_exploration.ipynb`  
  Initial data exploration and trend understanding
- `01_problem_framing.ipynb`  
  Translation of raw enrolment data into governance-relevant questions
- `02_signal_engineering.ipynb`  
  Design and detection of high-velocity migration signals

## Project Structure
- `notebooks/` – Analysis and signal development
- `assets/` – Visual outputs such as migration spike charts
- `docs/` – Supporting reports and reference material

## Key Output
- `top_migration_spikes.png`  
  Visualization highlighting districts with detected high-velocity migration signals

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- VS Code

## Author
Retesh  
UIDAI Data Hackathon 2026
