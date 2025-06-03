# 🚀 Remaining Useful Life Prediction of Aircraft Engine using Ensemble Neural Network and XGBoost Feature Selection

This repository contains the source code and dataset processing pipeline for a research project aimed at predicting the **Remaining Useful Life (RUL)** of aircraft engines. The approach combines **Ensemble Neural Networks** with **feature selection using XGBoost**, and compares multiple deep learning architectures: **LSTM**, **CNN-LSTM**, and **TCN**.

---

## 📌 Problem Statement

Predicting the Remaining Useful Life (RUL) of critical aircraft components is essential to ensure flight safety and optimize maintenance schedules. Due to the complex nature of engine degradation and operational variability, traditional methods often fall short in accuracy and adaptability.

---

## 🎯 Objectives

- To build a predictive model for aircraft engine RUL using **ensemble learning**.
- To evaluate the effectiveness of **XGBoost-based feature selection** in improving prediction performance.
- To compare the performance of multiple deep learning architectures (LSTM, CNN-LSTM, TCN) under both individual and ensemble configurations.

---

## 🧠 Methods

- **Dataset**: NASA CMAPSS (Commercial Modular Aero-Propulsion System Simulation)
- **Preprocessing**:
  - Feature selection using XGBoost
  - Feature normalization
  - Sliding window time series generation
- **Modeling**:
  - Training 15 individual models for each architecture
  - Weighted ensemble using inverse validation loss
- **Evaluation Metrics**:
  - RMSE (Root Mean Squared Error)
  - PICP (Prediction Interval Coverage Probability)
  - NMPIW (Normalized Mean Prediction Interval Width)

---
