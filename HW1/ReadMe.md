# First Homework

This collection includes my solutions to the assignments for the Fault Detection course, focusing on various statistical and machine learning techniques applied to fault detection in industrial systems.

## Homework Overview

### **Homework 1: Decision Boundaries and Risk Minimization**
In this homework, the focus is on the application of decision boundaries and risk minimization using Bayesian decision theory. The tasks include:

- **Classifying Faults**: Using a two-class problem setup, where one class represents normal conditions and the other represents faulty conditions, applying Gaussian distributions.
- **Decision Boundary Derivation**: Deriving decision boundaries using the Bayesian decision rule and minimizing risk.
- **Threshold Optimization**: Setting appropriate thresholds for classification based on the risk values and calculating the error probabilities.

### **Homework 2: Gamma Distribution and Fault Detection**
This homework focuses on detecting faults using Gamma distributions for both normal and faulty states:

- **Gamma Distribution Fitting**: Fitting Gamma distributions to normal and faulty states using the provided dataset.
- **Risk Calculation**: Analyzing decision errors and plotting probability density functions (PDFs) for both states.
- **Threshold Determination**: Finding optimal thresholds for classification between the two states and calculating decision errors.

### **Homework 3: Industrial Fault Detection with DAMADICS Dataset**
In this homework, we work with the DAMADICS dataset to detect faults in industrial actuator systems:

- **Data Preprocessing**: Handling the DAMADICS dataset, converting time-series data into a usable format for model training, and performing necessary data transformations.
- **Fault Classification**: Using statistical methods like Gaussian mixture models to classify different fault states in the industrial system.
- **Model Evaluation**: Evaluating the fault detection model using accuracy, confusion matrices, and F1 score, comparing performance across different fault types.

## Data Source

The dataset used in these homeworks is available at the following link:

- [DAMADICS Dataset](https://drive.google.com/file/d/1abGxLkOYkaYaQxHNKjLeIlAeAqeFAsr3/view?usp=sharing)

Please ensure you download and place the dataset in the appropriate directory for the code to function correctly.

## How to Run the Code

1. Clone this repository or download the notebook and MATLAB files.
2. Ensure the necessary libraries and dependencies are installed. For Python-based code, you can install the dependencies using:

   ```bash
   pip install -r requirements.txt
