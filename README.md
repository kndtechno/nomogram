# Nomogram Project

Survival analysis and nomogram development for cancer treatment outcomes.

## Description

This project contains analysis of cancer patient data including:
- Cox proportional hazards regression models
- Kaplan-Meier survival analysis
- Treatment effect analysis (RADIO, CIRURGIA, QUIMIO)
- DIAGTRAT (diagnosis to treatment time) analysis
- Nomogram development

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Jupyter notebook:
```bash
jupyter notebook nomogram.ipynb
```

## Data Files

- `bancorhc.csv` - RHC database
- `fosp-atualizado.xlsx` - FOSP database
- `UNIFICADO ATUALIZADA.xlsx` - Unified database

## Analysis

The main analysis is in `nomogram.ipynb` which includes:
- Data preprocessing and merging
- Survival analysis by treatment groups
- Cox regression models
- DIAGTRAT threshold analysis
- Visualizations

