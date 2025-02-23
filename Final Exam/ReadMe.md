# Final Exam Solutions

This collection includes my solutions to the final exam, covering various topics in fault detection, including model-based fault diagnosis, PCA, LDA, and methods like Parity, Factorization, and Kalman filters.

## Exam Overview

### **Question 1: Fault Detection Using Factorization Methods**
This question focuses on fault detection using factorization methods:

- **Factorization Approach**: Applying factorization methods for fault detection, including designing models that use input-output relationships to isolate faults in sensors and actuators.
- **Sensor Fault Detection**: Using the designed models to detect sensor faults through output relationships and factorization techniques.

### **Question 2: Observer-Based Fault Detection**
This question discusses the design of observers for fault detection:

- **Observer Design**: Designing an observer for detecting faults in unknown inputs, specifically for identifying faults in actuators and sensors.
- **Unknown Input Observer**: Using an observer to detect faults in the system where input disturbances or faults are not directly observable.

### **Question 3: Parity-Based Fault Detection**
This question focuses on using parity-based methods for fault detection:

- **Parity Method Application**: Using the parity-check method to detect faults, applying it to sensor and actuator systems for fault isolation and detection.
- **Fault Isolation Using Parity**: Isolating faults in a system by employing the parity method and verifying the results with various fault conditions.

### **Question 4: PCA and LDA for Fault Classification**
This question explores dimensionality reduction and classification using PCA and LDA:

- **Principal Component Analysis (PCA)**: Using PCA to reduce the dimensionality of fault detection data, improving classification performance.
- **Linear Discriminant Analysis (LDA)**: Applying LDA to find projections that minimize within-class variance and maximize between-class variance, improving fault detection classification.

### **Question 5: Model-Based Fault Diagnosis Using FFT**
This question involves fault diagnosis based on frequency domain analysis:

- **Frequency Domain Analysis**: Using FFT (Fast Fourier Transform) to analyze the frequency components of signals for fault detection, and applying this analysis to bearing fault detection.
- **Fault Classification**: Classifying different types of faults using neural networks based on frequency-domain features extracted from FFT analysis.

### **Question 6: Neural Network Design for Fault Detection**
This question focuses on designing and training a neural network for fault detection:

- **Neural Network Design**: Designing a neural network for fault classification based on features derived from FFT and PCA.
- **Network Training**: Training the network using a dataset and evaluating its performance using accuracy, confusion matrices, and classification metrics.

## How to Run the Code

1. Clone this repository or download the notebook files.
2. Install the required libraries. You can install the dependencies using:

   ```bash
   pip install -r requirements.txt
