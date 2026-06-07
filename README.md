# Personalized Diabetes Treatment Response Prediction

## Overview

Selecting the optimal glucose-lowering therapy for patients with Type 2 Diabetes remains a major clinical challenge because treatment response varies substantially between individuals.

This project investigates whether longitudinal deep learning models can improve prediction of 12-month HbA1c response compared with traditional machine learning approaches using electronic health record (EHR) data from more than 94,000 patients and 120,000 treatment initiation events.

Models evaluated included:

- HistGradientBoostingRegressor (HGBR)
- Elastic Net
- Convolutional Neural Network (CNN)
- Gated Recurrent Unit (GRU)

## Key Findings

- HGBR achieved the best overall performance
- Longitudinal GRU models did not outperform simpler tabular approaches
- Outcome definition substantially influenced predictive performance
- Data quality and representation were more important than model complexity

## Technologies

Python, Scikit-Learn, PyTorch, Deep Learning, EHR Data, Healthcare AI, Precision Medicine
