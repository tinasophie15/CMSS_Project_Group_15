# Inequality and Polarization: An Agent-Based Modeling Approach Using Eurostat Data

by CMSS Group 15:
- Kevin Heinrich, 11902941
- Matthias Hemmer, 11804194
- Marina Hofer, 12337819
- Christina Sophie Knes, 11902902

## Overview

This project investigates the link between **income inequality** and **social polarization** across European regions using an **agent-based model (ABM)**. We integrate real-world data from [Eurostat](https://ec.europa.eu/eurostat), including **Gini coefficients**, **at-risk-of-poverty rates**, **regional household income** and **unemployment rate** to simulate how economic disparities influence opinion dynamics.

The model builds on the Deffuant bounded confidence framework, enriched with income-based heterogeneity and frustration levels. By simulating regional populations with varying inequality levels, we aim to explore under which conditions **polarization**, **extremism** or **opinion fragmentation** emerge.

## Features

- Opinion dynamics based on Deffuant model
- Real Eurostat income and inequality data (Countries in Europe)
- Visualizations of polarization outcomes by region and years

## Data Sources

All datasets are publicly available via the [Eurostat Data Browser](https://ec.europa.eu/eurostat/databrowser/):

- [Mean and median income by age and sex](https://ec.europa.eu/eurostat/databrowser/view/ilc_di03/default/table?lang=en) (code: ilc_di03)
- [Gini coefficient of equivalised disposable income by age](https://ec.europa.eu/eurostat/databrowser/view/ilc_di12/default/table?lang=en) (code: ilc_di12)
- [At-risk-of-poverty rate by poverty threshold, age and sex](https://ec.europa.eu/eurostat/databrowser/view/ilc_li02/default/table?lang=en) (code: ilc_li02)
- [Share of housing costs in disposable household income, by type of household and income group](https://ec.europa.eu/eurostat/databrowser/view/ilc_mded01/default/table?lang=en) (code: ilc_mded01)
- [Unemployment by sex and age - annual data](https://ec.europa.eu/eurostat/databrowser/view/une_rt_a/default/table?lang=en) (code: une_rt_a)

## Requirements

- Python 3.13+
- Libraries: `eurostat`, `mesa`, `pandas`, `matplotlib`, `seaborn`, `numpy`, `geopandas`, `scipy`, `adjustText`
