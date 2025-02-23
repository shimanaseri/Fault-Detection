# Forth Homework

This collection includes my solutions to the fourth and fifth series of assignments for the Fault Detection course. The tasks focus on fault detection, fault isolation, and adaptive filtering using various methods, including Parity Factorization, Kalman filters, and observer design.

## Homework Overview

### **Homework 1: Parity and Factorization Methods**
This homework focuses on fault detection using Parity and Factorization methods:

- **Parity Methods**: Designing a system to detect faults based on parity checks. The task involves computing residuals and isolating faults by comparing outputs with expected behaviors.
- **Factorization**: Using factorization techniques to develop an observer for fault detection. The approach includes developing a model and analyzing fault detection performance.
- **Signal Processing**: Using various signal processing techniques to handle unknown disturbances and designing an observer that can detect faults in the system's state variables.

### **Homework 2: Fault Isolation Using Adaptive Filtering**
This homework involves designing adaptive filters for fault isolation:

- **Adaptive Filtering**: Implementing adaptive filters like the Kalman filter for detecting and isolating faults in system states.
- **Design and Evaluation**: Testing the adaptive filter on industrial datasets and evaluating the performance for different fault conditions.
- **Fault Isolation**: Determining how well the filter isolates faults in the system and analyzing its effectiveness under different disturbances.

### **Homework 3: Observer Design for Fault Detection**
This homework involves designing and implementing observers for fault detection:

- **Observer Design**: Developing a fault detection observer for a given system model, ensuring it can detect faults in all state variables.
- **Kalman Filter Implementation**: Using Kalman filtering techniques for fault isolation and estimation.
- **Evaluation and Results**: Analyzing the fault detection performance of the designed observer and providing insights into its effectiveness in various conditions.

### **Homework 4: Parity Factorization with Faults**
This homework continues with the Parity and Factorization methods but introduces fault detection for more complex scenarios:

- **Observer Design with Faults**: Implementing an observer to handle faults in different parts of the system. This includes detecting faults with additional disturbances and ensuring the observer works under various fault scenarios.
- **Factorization with Faults**: Designing fault detection systems with factorization approaches to handle situations where faults are added to the system.

### **Homework 5: Advanced Fault Detection**
This final homework dives deeper into fault detection methods with a focus on complex scenarios:

- **Observer-Based Fault Detection**: Using an observer-based method for detecting faults in various states, ensuring that faults can be isolated and identified.
- **Parity Methods with Faults**: Implementing and analyzing parity-based methods to detect faults with the system.
- **Fault Detection with Adaptive Filtering**: Implementing adaptive filtering techniques to isolate faults from the system states and analyzing how well these methods perform when faults occur.

## Data Source

The dataset for these assignments is available at the following link:

- [Fault Detection Dataset on Google Drive](https://drive.google.com/file/d/1o72UZ4KYSlT62tB7iG-AfuHoj3N2Pe8z/view?usp=sharing)

Make sure to download and use this data for the exercises.

## How to Run the Code

1. Clone this repository or download the notebook and MATLAB files.
2. Install the required libraries. You can install the dependencies using:

   ```bash
   pip install -r requirements.txt
