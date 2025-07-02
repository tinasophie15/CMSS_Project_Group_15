# Inequality and Polarization: An Agent-Based Modeling Approach Using Eurostat Data

by CMSS Group 15:
- Kevin Heinrich, 11902941
- Matthias Hemmer, 11804194
- Marina Hofer, Matrikelnummer
- Christina Sophie Knes, 11902902

## Overview

This project investigates the link between **income inequality** and **social polarization** across European regions using an **agent-based model (ABM)**. We integrate real-world data from [Eurostat](https://ec.europa.eu/eurostat), including **Gini coefficients**, **at-risk-of-poverty rates**, and **regional household income**, to simulate how economic disparities influence opinion dynamics.

The model builds on the Deffuant bounded confidence framework, enriched with income-based heterogeneity and frustration levels. By simulating regional populations with varying inequality levels, we aim to explore under which conditions **polarization**, **extremism** or **opinion fragmentation** emerge.

## Features

- Opinion dynamics based on Deffuant model
- Real Eurostat income and inequality data (NUTS-2)
- Visualizations of polarization outcomes by region and scenario
- Experiments with redistribution policies and inequality shocks

## Data Sources

- Gini coefficient: `ilc_di12`  
- At-risk-of-poverty rate: `ilc_li02`  
- Regional differences: `ilc_mded01`

All datasets are publicly available via the [Eurostat Data Browser](https://ec.europa.eu/eurostat/databrowser/).

## Requirements

- Python 3.13+
- Libraries: `mesa`, `pandas`, `matplotlib`, `seaborn`, `numpy`
