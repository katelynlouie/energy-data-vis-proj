# Data Visualization Project: NYC Building Energy & Emissions Analysis

**Course:** CS 101 — Survey of CS in Python  
**Authors:** Katelyn Louie, Tasnia Ahmed  
**Tools:** Python, Pandas, Matplotlib, Seaborn, Jupyter Notebooks  

---

## Project Overview
This project investigates energy efficiency and greenhouse gas (GHG) emissions across New York City buildings using data disclosed under **NYC Local Law 84**. By analyzing building characteristics, location metrics, and performance scores, this study explores key spatial and operational patterns to inform urban sustainability and architectural decision-making.

---

## Core Questions & Findings

### 1. Where are GHG emissions concentrated across NYC? *(Geospatial Heatmap)*
* **Approach:** Density analysis using Latitude, Longitude, and Location-Based GHG Emissions Intensity ($\text{kgCO}_2\text{e}/\text{ft}^2$).
* **Key Finding:** Emissions intensity is heavily concentrated in high-density commercial and residential corridors, with a major hotspot centered around Midtown Manhattan. Tighter clusters highlight high-priority zones for target decarbonization and retrofits.

### 2. How do ENERGY STAR Scores differ across building types? *(Distribution Analysis)*
* **Approach:** Comparative boxplot analysis of ENERGY STAR scores (1–100 scale) filtered across the top primary property categories.
* **Key Finding:** Office buildings consistently lead in performance, frequently achieving top-performer status ($>75$). Conversely, Multifamily Housing and K-12 Schools show broader distributions and lower median scores, reflecting differences in building age, usage patterns, and capital resources.

### 3. How is Site Energy Use Intensity (EUI) distributed across NYC buildings in 2022? *(Baseline Analysis)*
* **Approach:** Median imputation and outlier filtering (capped at 95th percentile) to assess 2022 baseline energy consumption per square foot ($\text{kBtu}/\text{ft}^2$).
* **Key Finding:** Building energy use exhibits a right-skewed distribution with a baseline median of $\sim77\text{ kBtu}/\text{ft}^2$. While the majority of properties cluster at moderate consumption levels, a subset of high-EUI outliers represents key opportunities for energy efficiency upgrades.

---

## Repository Structure
```text
├── cs101_data_vis_katelyn_tasnia_polished.ipynb              # Primary Jupyter Notebook with analysis & plots
├── reduced_df.csv                                            # Processed NYC building energy dataset
├── requirements.txt                                          # Project dependencies
├── Data_Vis_Proj_Katelyn_Tasnia_Energy Constellations copy   # Final presentation poster
└── README.md                                                 # Project documentation