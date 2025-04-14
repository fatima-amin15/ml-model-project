# Predictive Maintenance for Medical Laser Machines

This machine learning project simulates a predictive maintenance system for laser machines used in medical manufacturing.

## Overview

We use synthetic data to predict potential machine failures based on operational parameters such as temperature, vibration, usage hours, and error codes.

## Setup

```bash
conda create -n ml-model python=3.10 -y
conda activate ml-model
pip install -r requirements.txt

## 📊 Laser Machine Failure Prediction

This notebook focuses on predicting machine failure in a medical manufacturing setting using synthetic sensor data such as temperature, pressure, vibration, and more.

### Features:
- **Synthetic Data Generation** simulating real-world conditions in laser machines.
- **Handling Class Imbalance** using SMOTE to better learn from rare failure cases.
- **Random Forest Classifier** trained on scaled and balanced data.
- **Performance Metrics** include accuracy, precision, recall, and confusion matrix.

### File:
- 📁 `notebooks/laser_failure_prediction.ipynb`
