
# Multi-Source LSTM-Based Forecasting of Dissolved Oxygen in the Ganga River

## 📌 Overview

This project develops a deep learning-based framework for short-term water quality forecasting in the Ganga River basin. Specifically, we predict next-day Dissolved Oxygen (DO) levels using historical monitoring data and meteorological variables.

The goal is to evaluate whether multi-source data fusion improves forecasting accuracy compared to historical-only models.

This work is intended for conference-level publication and demonstrates an end-to-end AI pipeline for environmental time-series prediction.

---

## 🎯 Problem Statement

Water quality in the Ganga River fluctuates due to rainfall, temperature variations, discharge, and anthropogenic activities. Current monitoring systems are largely reactive rather than predictive.

There is a need for a data-driven forecasting framework that can:

- Predict short-term water quality variations
- Integrate multiple environmental data sources
- Support real-time decision-making systems

---

## 🧠 Research Objective

To design and evaluate an LSTM-based forecasting model for 1-day-ahead Dissolved Oxygen prediction using:

1. Historical water quality measurements
2. Meteorological variables (rainfall, temperature)
3. Comparative multi-source fusion experiments

---

## 🔬 Methodology

The study follows these steps:

1. Data Collection
   - Water quality data from CPCB monitoring stations
   - Meteorological data (rainfall, temperature)

2. Data Preprocessing
   - Missing value handling
   - Temporal alignment
   - Normalization
   - Sliding window sequence generation

3. Model Development
   - Baseline LSTM model (historical-only)
   - LSTM with weather data fusion
   - PyTorch implementation

4. Evaluation Metrics
   - RMSE (Root Mean Squared Error)
   - MAE (Mean Absolute Error)
   - R² Score

5. Comparative Analysis
   - Historical-only vs Multi-source input

---

## 📊 Forecasting Setup

- Target Variable: Dissolved Oxygen (DO)
- Forecast Horizon: 1-day ahead
- Temporal Resolution: Daily
- Study Region: Ganga River Basin
- Model Type: LSTM (Long Short-Term Memory)

---

## 📁 Project Structure
