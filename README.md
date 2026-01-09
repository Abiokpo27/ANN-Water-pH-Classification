# ANN-Water-pH-Classification
Graduate-level coursework project applying a feedforward artificial neural network (ANN) to binary classification of water pH levels using sensor data, with attention to preprocessing, class imbalance, and model validation.

## View Notebook
If GitHub does not render the notebook correctly:
- ANN notebook (nbviewer): https://nbviewer.org/github/Abiokpo27/ANN-Coursework-Project/blob/main/BSE5124_NN_Batubo_ANN.ipynb

# ANN for Water pH Classification

This repository contains a graduate-level coursework project focused on applying an artificial neural network (ANN) to water quality monitoring.

## Project Overview
The project addresses water security by modeling water pH levels using sensor-based time series data. A feedforward ANN is used to perform binary classification of pH values, distinguishing between readings above neutral (>7) and neutral or below (≤7).

## Data
The dataset consists of pH and temperature sensor readings, along with device and signal indicators, including battery level, signal strength (RSSI), and reading counters. These features reflect both water conditions and sensor reliability.

## Methodology
A feedforward artificial neural network was implemented using the Keras Sequential API. Multiple architectures, activation functions, batch sizes, and training epochs were evaluated. Stratified k-fold cross-validation and SMOTE were used to address class imbalance, and feature scaling was applied to ensure stable training.

## Results Summary
The final ANN configuration achieved high classification accuracy on the available data. However, the near-perfect performance highlighted the importance of caution when interpreting results from small or highly structured datasets, reinforcing the need for careful validation.

## Files
- `BSE5124_NN_Batubo_ANN.ipynb` - ANN implementation and evaluation

## Notes
This work reflects my individual coursework and learning process.
