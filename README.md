# smi-youth-employment-did
R code and data panels for my Bachelor's Thesis (TFG): "Impact of the SMI increase on youth employment: an approach in Spain based on average per capita income" using a Difference-in-Differences (DiD) framework with regional fixed effects.
# Impact of the SMI Increase on Youth Employment in Spain (2010-2023)

This repository contains the econometric code, datasets, and the full text of my Bachelor's Thesis (*Trabajo de Fin de Grado* - TFG) in Economics at the **Universitat de Barcelona (UB)**.

* **Author:** Santiago Vázquez Collado
* **Advisor:** Ramon Franquesa Artés
* **Academic Year:** 2025-2026

---

## 📊 Project Overview
The objective of this research is to evaluate whether the aggressive increases in the Spanish Minimum Wage (*Salario Mínimo Interprofesional* - SMI) since 2017 caused a differential negative impact on youth employment in regions with lower average income per capita. 

### Methodology
The study implements a **Difference-in-Differences (DiD)** econometric framework using a balanced panel data structure across 17 Spanish Autonomous Communities (CCAA) from 2010 to 2023. The models control for macroeconomic factors, labor costs, regional economic structures, and demographic trends, incorporating **Region and Year Fixed Effects** with standard errors clustered at the regional level.

Key time windows analyzed:
* **Post-treatment 1 (2017–2019):** Initial SMI structural increments.
* **Post-treatment 2 (2020–2023):** Evaluation of subsequent adjustments and longer-term resilience.
* **Aggregate Period (2017–2023):** Comprehensive impact evaluation.

---

## 📂 Repository Structure
* `TFG_Vázquez Collado, Santiago.pdf`: Full text of the thesis (in Spanish), including literature review, descriptive analysis, and economic discussions.
* `R proyecto final.R`: Clean, production-ready R script containing the full econometric workflow (`fixest` package implementation).
* `Resultados_DiD_Modelos_SMI.txt`: Automatically generated output containing the replication summaries, coefficients, standard errors, and diagnostic statistics (AIC, Wald F-test).
* `*.xlsx`: Raw data panels sourced from the National Statistics Institute (INE) covering youth employment, GDP per capita, labor costs, and sectoral structures.

---

## 🚀 How to Replicate the Results
1. Clone or download this repository.
2. Ensure you have the required packages installed in R: `install.packages(c("readxl", "dplyr", "fixest"))`.
3. Open the R script and adjust the working directory (`setwd()`) on line 11 to match your local path.
4. Run the script. It will automatically merge the data, execute the 8 structural models, and export the comprehensive summary to the text file.

