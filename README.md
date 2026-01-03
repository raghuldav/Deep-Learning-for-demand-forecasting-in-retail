# Deep Learning for Demand Forecasting in Retail

## Overview
This project presents a comprehensive evaluation of **deep learning–based forecasting models** for **multi-step demand prediction** in the retail sector. Using the **Warehouse and Retail Sales dataset (300,000+ records)**, the study analyzes model performance under both **clean data conditions** and **synthetically perturbed data**, reflecting real-world uncertainty and noise.

The objective is to assess not only predictive accuracy but also **robustness and stability** across different neural architectures.

---

## 🧠 Models Evaluated
The following models were implemented and compared:

- Linear Regression  
- Feedforward Neural Network (FNN)  
- Long Short-Term Memory (LSTM)  
- Gated Recurrent Unit (GRU)  
- Transformer  
- CNN–RNN Hybrid  

---

## 📊 Dataset
- **Source:** Data.gov – Warehouse and Retail Sales  
- **Size:** 307,000+ records  
- **Key Features:**  
  - Year  
  - Month  
  - Supplier  
  - Item Type  
  - Retail Sales  
  - Warehouse Sales  

---

## 🔍 Methodology
The forecasting pipeline includes the following stages:

- Data cleaning and missing value handling using **Random Forest–based Iterative Imputation**
- Feature engineering with **log transformations**, **lag features**, and **scaling**
- Time series exploratory analysis and seasonality detection
- **Synthetic Gaussian noise injection** to evaluate robustness
- Model training and testing on both **clean and noisy datasets**
- Performance comparison using **MSE, MAE, RMSE, and R²**

---

## 📈 Key Findings
- **GRU** consistently delivered the strongest performance across both clean and noisy datasets.
- **Transformer models** demonstrated high resilience, maintaining competitive accuracy even under noise injection.
- Traditional regression and feedforward models showed limited robustness compared to sequence-based architectures.

---

## Conclusion
This study highlights the effectiveness of **recurrent and attention-based deep learning models** for retail demand forecasting. By evaluating performance under realistic noise conditions, the project provides valuable insights into model selection for production-grade forecasting systems operating in uncertain environments.
