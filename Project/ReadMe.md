# Fault Detection Project

This project is divided into two phases, where the first phase focuses on data preprocessing, feature extraction, and basic fault detection techniques, and the final phase enhances the models with advanced machine learning techniques, regularization, and optimization strategies.

## Project Overview

### **Phase 1: Fault Detection and Classification**
In the first phase, the primary goal was to preprocess the data, apply dimensionality reduction, and develop initial models for fault detection. The key tasks included:

- **Data Collection and Preprocessing**: 
  The dataset used for this phase is based on **Simulated Boiler Data for Fault Detection and Classification**, which includes parameters such as temperature, pressure, and flow rate. The data was preprocessed using scaling, handling missing values, and outlier detection.
  
- **Dimensionality Reduction**: 
  We applied several dimensionality reduction techniques to improve the efficiency of fault classification:
  - **t-SNE**: A non-linear technique for reducing dimensionality while preserving local structures.
  - **Autoencoders**: A neural network-based approach for unsupervised feature learning and dimensionality reduction.
  - **PCA**: A linear method that reduces the number of features while retaining important information.

- **Fault Detection**: 
  The task involved detecting different types of faults in the boiler system. A neural network was trained to classify the data into different fault categories using the reduced features.

- **Model Evaluation**: 
  We evaluated the models using metrics such as confusion matrices, Silhouette Score, and Calinski-Harabasz Index to assess clustering and classification performance.

### **Phase 2: Advanced Fault Detection and Classification**
In the final phase, the focus shifted to refining the models using advanced machine learning techniques, regularization, and optimization strategies. Key tasks included:

- **Model Development**:
  We implemented several machine learning models for fault classification, including:
  - **MLP (Multi-Layer Perceptron)**: A fully connected neural network trained on the preprocessed data.
  - **CNN (Convolutional Neural Network)**: Applied to extract spatial features for fault classification.
  - **Hybrid Networks**: Combining CNN and LSTM (Long Short-Term Memory) for enhanced temporal feature extraction.
  - **Transformer Networks**: Leveraging attention mechanisms for better classification of faults.

- **Regularization and Optimization**:
  Regularization methods such as **Dropout** and **L2 regularization** were used to prevent overfitting. Additionally, techniques like **ReduceLROnPlateau** were implemented to optimize model performance and convergence during training.

- **Model Evaluation**:
  Each model's performance was evaluated using metrics such as AUC, F1 Score, Recall, Precision, and confusion matrices. The best model was identified based on these metrics for fault classification.

### **Key Methods Used**
- **Regularization**: Dropout, L2 regularization to prevent overfitting.
- **Feature Reduction**: PCA, t-SNE, Autoencoders, LDA for dimensionality reduction.
- **Neural Networks**: MLP, CNN, Hybrid networks, Transformer models for fault classification.


## How to Run the Code

1. Clone this repository or download the notebook files.
2. Install the required libraries. You can install the dependencies using:

   ```bash
   pip install -r requirements.txt
