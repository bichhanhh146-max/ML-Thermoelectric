## Thermal Conductivity Prediction Model

This repository provides a **trained model** for predicting the thermal conductivity of thermoelectric materials and multi-component materials from **thermoelectric materials composition** and **temperature**. The trained model artifacts are **uploaded to this GitHub repo** so that others can directly run inference without retraining.

### Summary

- We built the **large experimental dataset** with **13,104 data points**, spanning **73 elements** and temperatures from **0 to 1481 K**.
- Using **composition and temperature** as inputs, we train and benchmark multiple regression models and achieve **R² > 0.96** with **RMSE ≈ 0.37-0.54 W/m·K**.

### Inputs / Output

**Inputs**
- Thermoelectric materials composition
- Temperature **T (K)**

**Output**
- Thermal conductivity **κ (W/m·K)**
