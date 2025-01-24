# 📊 Time Series Analysis Lab Experiments 

**Course:** Advanced Data Analysis & Forecasting  
**Department:** Artificial Intelligence and Machine Learning  
**Academic Year:** 2025  
**Roll No:** 221501030


## 🔧 Tools & Technologies
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0.3-red)
![Statsmodels](https://img.shields.io/badge/Statsmodels-0.14.0-green)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13.0-orange)


 
**Lab Cycle:** *10 Critical Experiments for Time Series Forecasting*  

---

## 🧪 Experiment List  

### 🔍 **Core Techniques**  
| Experiment | Description | Tools Used |  
|------------|-------------|------------|  
| **1. Data Preprocessing** | Missing value handling, outlier detection, deduplication | `Pandas`, `NumPy` |  
| **2. Visualization** | Temporal patterns, decomposition plots | `Matplotlib`, `Seaborn` |  
| **3. Stationarity Check** | ADF test, rolling statistics analysis | `statsmodels` |  

### 📈 **Trend & Seasonality**  
| Experiment | Key Methods |  
|------------|-------------|  
| **4. Trend Estimation** | Moving averages, polynomial fitting |  
| **5. Smoothing** | Exponential smoothing, LOESS |  
| **6. Decomposition** | Additive vs multiplicative decomposition |  

### 🤖 **Forecasting Models**  
| Experiment | Model Type | Complexity |  
|------------|------------|------------|  
| **7. Linear Regression** | Baseline forecasting | Low |  
| **8. ARIMA** | Autoregressive integrated model | Medium |  
| **9. LSTM** | Deep learning approach | High |  
| **10. VAR** | Multivariate forecasting | High |  

---

## 🗂️ Experiment Workflow  

```mermaid  
graph TD  
  A[Raw Data] --> B(Preprocessing)  
  B --> C{Analysis}  
  C --> D[Stationarity Check]  
  C --> E[Trend Estimation]  
  C --> F[Seasonality Decomposition]  
  D --> G[Model Selection]  
  E --> G  
  F --> G  
  G --> H[Forecast Evaluation]  
