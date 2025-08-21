# 📊 Impact of Demographic Growth on Economic Growth in France (1960–2023)

![GitHub last commit](https://img.shields.io/github/last-commit/username/repo?style=flat-square&color=blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![Made with](https://img.shields.io/badge/Made%20with-Python%20%26%20Excel-orange?style=flat-square)
![License](https://img.shields.io/badge/License-Academic-blueviolet?style=flat-square)

---

## 📑 Table of Contents
- [🎯 Objective](#-objective)
- [📂 Data Sources](#-data-sources)
- [🛠️ Methodology](#️-methodology)
- [📈 Key Findings](#-key-findings)
- [✅ Conclusion](#-conclusion)
- [📚 References](#-references)

---

## 🎯 Objective
Assess whether **demographic growth fosters economic growth in France**, and identify the **main determinants of GDP per capita** over 1960–2023.

---

## 📂 Data Sources
- **Excel Database**: `data_base.xlsx`  
- **Python Notebook**: `Projet_THE_Ange & Roumbo_Philippe.ipynb`  
- **Full Report**: `Rapport_Projet_THE.pdf`  
- **Official Data**: INSEE, World Bank, OECD, Eurostat, UNDP  

---

## 🛠️ Methodology
1. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics of GDP/capita, inflation, savings, trade balance.  
   - Historical context: oil shocks, subprime crisis, Covid-19.  
   - Key correlations (e.g., GDP/FBCF = 82%).  

2. **Linear Regression Model**  
   - Adjusted R² = 81%  
   - Normally distributed residuals, multicollinearity issues detected.  
   - Significant variables:  
     - FBCF (+), Savings (+)  
     - Demographic growth (–), Employment (–), Taxes (–).  

3. **Time Series Modeling (SARIMAX)**  
   - Final model: **SARIMAX(1,0,3)** with FBCF & savings as exogenous variables.  
   - Better shock management than linear regression.  
   - Performance: R² ≈ 81% (train), 54% (test).  

---

## 📈 Key Findings
- 📉 **Demographic growth**: negative or non-significant effect on GDP per capita.  
- 📊 **FBCF (investment)**: main driver of growth.  
- 💰 **Savings**: positive but moderate effect.  
- ⚖️ **Taxes & employment**: negative effects, suggesting structural rigidities.  
- 🔄 **Economic shocks**: strong impact, partly absorbed in SARIMAX dynamics.  

---

## ✅ Conclusion
Demographic growth **is not a key determinant of economic growth in France**.  
Instead, **investment, savings, and innovation** are the main long-term growth drivers.  
Public policies should therefore focus on:  
- 🚀 Boosting productive investment,  
- 📈 Fostering innovation and competitiveness,  
- 🌍 Efficient integration of migration inflows.  

---

## 📚 References
- [INSEE](https://www.insee.fr)  
- [World Bank](https://data.worldbank.org)  
- [OECD](https://data.oecd.org)  
- [UNDP](https://hdr.undp.org)  
- [Eurostat](https://ec.europa.eu/eurostat)  

---

👤 **Authors**:  
- Philippe Roumbo *(M1 BIDABI)*  
- Ange-Paul Emmanuel THE *(M1 BIDABI)*  
Université Sorbonne Paris Nord — 2024/2025
