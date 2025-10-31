# 🌦️ Climate Variability and Large-Scale Pattern Analysis

This project analyzes **climate variability from 1950–2023** using statistical techniques such as **Empirical Orthogonal Function (EOF)** analysis, **correlation**, and **regression** to study global and regional patterns in **SST, SAT, and wind anomalies**.


---

## 🎯 Objectives
- Study **temporal and spatial variability** in key climate parameters.  
- Identify dominant **modes of variability** using EOF analysis.  
- Correlate major **climate indices (ENSO, IOD, PDO, AMO)** with observed datasets.

---

## 🧰 Tools & Data
- **Python (xarray, netCDF4, numpy, matplotlib)**  
- **Climate Datasets:** NOAA, ERA5, HadISST (1950–2023)  
- **Variables:** Sea Surface Temperature (SST), Surface Air Temperature (SAT), U/V winds  

---

## ⚙️ Methodology
1. Import and preprocess netCDF data.  
2. Detrend and standardize time series.  
3. Apply **EOF analysis** to extract dominant spatial-temporal modes.  
4. Compute correlations between principal components and global indices (ENSO, IOD, etc.).  
5. Visualize anomaly patterns and temporal variability.

---

## 📈 Key Results
| Mode | Variance Explained | Dominant Region | Linked Index |
|------|--------------------|-----------------|---------------|
| EOF-1 | 42% | Tropical Pacific | ENSO |
| EOF-2 | 18% | Indian Ocean | IOD |
| EOF-3 | 9% | North Atlantic | AMO |

**EOF Spatial Patterns**  
![EOF Patterns](Results/eof_modes.png)

**Time Series Comparison**  
![Timeseries](Results/index_correlation.png)

---

## 🧠 Learning Outcomes
- Learned advanced **statistical climate analysis techniques**.  
- Interpreted **large-scale teleconnections** (ENSO, IOD, PDO).  
- Built end-to-end workflows for **climate data visualization** in Python.

---

## 📄 Project Report

You can read the full detailed report here:  
[📘 **Climate Variability and Large-Scale Pattern Analysis - Report**](Climate_Variability_Report.pdf)

The report includes methodology, data preprocessing, EOF analysis results, and visual interpretation of major climate indices.


## 📂 Repository Structure
