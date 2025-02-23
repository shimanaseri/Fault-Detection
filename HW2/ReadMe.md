# Fault Detection Homework Repository

This collection includes my solutions to the second series of assignments for the Fault Detection course, focusing on different statistical techniques for fault detection in industrial systems, including Maximum Likelihood Estimation (MLE), non-parametric methods, and data preprocessing.

## Homework Overview

### **Homework 1: Maximum Likelihood and MAP Estimation**
This homework focuses on the estimation of parameters using Maximum Likelihood Estimation (MLE) and Maximum A Posteriori (MAP) estimation for different distributions. The tasks include:

- **MLE and MAP Estimation**: Deriving the MAP estimate for a given dataset and comparing it to the MLE.
- **Decision Boundary Analysis**: Using decision theory to find thresholds and boundaries for classifying normal and faulty conditions.
- **Statistical Comparison**: Analyzing the difference in performance between MLE and MAP under various conditions.

### **Homework 2: Non-Parametric Methods for Fault Detection**
This homework explores non-parametric estimation methods for fault detection:

- **Parzen Window Estimator**: Using the Parzen window method to estimate probability density functions for fault detection.
- **Bias and Variance Analysis**: Calculating and analyzing the bias and variance of the Parzen method.
- **Performance Comparison**: Comparing non-parametric methods with parametric methods and evaluating their effectiveness in fault detection tasks.

### **Homework 3: Fault Detection with DAMADICS Dataset**
In this homework, we work with the DAMADICS dataset to detect faults in industrial actuator systems:

- **Data Preprocessing**: Processing time-series data and normalizing it for further analysis.
- **Fault Detection Models**: Using techniques like KNN, SVM, and Gaussian mixture models to detect faults.
- **Model Evaluation**: Evaluating the performance of models using metrics like accuracy, confusion matrices, and F1 score.

## How to Run the Code

1. Clone this repository or download the notebook and MATLAB files.
2. Install the required libraries. You can install the dependencies using:

   ```bash
   pip install -r requirements.txt
