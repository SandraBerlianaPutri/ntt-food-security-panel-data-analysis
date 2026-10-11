# Factors Associated with Food Security in East Nusa Tenggara

## About
This project examines factors associated with the Food Security Index (IKP) across regencies in East Nusa Tenggara, Indonesia, using panel data regression. The analysis compares pooled, fixed-effects, and random-effects models, followed by model selection tests and diagnostic checks.

## Project Analysis
- [Read the Full Analysis on RPubs](https://rpubs.com/sandraberlianaputri/panel-data-food-security-ntt)
- [Read the Published Journal Article](https://jstar.id/ojs/index.php/JSTAR/article/view/140/87)

## Dataset
- **Geographic coverage:** 22 regencies in East Nusa Tenggara, Indonesia
- **Study period:** 2020–2022
- **Observations:** 66 records in a balanced panel
- **Response variable:**
  - `IKP`: Food Security Index
- **Predictor variables:**
  - `AHH`: Life expectancy
  - `PDRB`: Gross Regional Domestic Product (GRDP)
  - `Prod.Pangan`: Food production
- **Additional variables:** `IPM` (Human Development Index) and `IKP_cat` (Food Security Index category)
  
## Methods
- **Panel Data Preparation:** Defined regency and year as panel indices using `plm`.
- **Model Estimation:** Pooled OLS, Fixed Effects Model (FEM), and Random Effects Model (REM).
- **Model Selection:** Chow test, Hausman test, and Breusch–Pagan Lagrange Multiplier test.
- **Multicollinearity Assessment:** Variance Inflation Factor (VIF).
- **Residual Diagnostics:** Shapiro–Wilk and Jarque–Bera normality tests, Breusch–Pagan heteroscedasticity test, and Kolmogorov–Smirnov test.

## Publication
**Factors Affecting the Food Security Index in East Nusa Tenggara Province Using Panel Data Analysis**

Published in JSTAR, June 2026.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
