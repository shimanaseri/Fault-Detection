# Third Homework

This collection includes my solutions to the third series of assignments for the Fault Detection course. The tasks focus on using machine learning models, such as Neural Networks (RBF and MLP), along with dimensionality reduction techniques for fault classification in industrial systems.

## Homework Overview

### **Homework 1: Decision Boundaries and Fault Classification**
This homework focuses on deriving decision boundaries and performing fault classification using neural networks. The tasks include:

- **Decision Boundaries**: Defining decision boundaries for two classes, normal and faulty, and visualizing these boundaries in a feature space.
- **Neural Network Classification**: Using MLP and RBF networks for fault classification and training the models with gradient descent and other optimization techniques.
- **Model Evaluation**: Evaluating the models based on accuracy and analyzing the performance of the neural networks for different configurations.

### **Homework 2: Feature Engineering and Dimensionality Reduction**
In this homework, the goal is to preprocess and reduce the dimensionality of the dataset to improve fault classification performance:

- **Feature Extraction**: Calculating statistical features such as standard deviation, peak, skewness, and kurtosis from the data.
- **Dimensionality Reduction**: Using techniques like PCA, LDA, t-SNE, and Autoencoders to reduce dimensionality and evaluate their effect on classification accuracy.
- **Model Training and Evaluation**: Applying the reduced dataset to train fault detection models and comparing the results before and after dimensionality reduction.

### **Homework 3: Synthetic Data Generation for Fault Detection**
This homework involves generating synthetic data for fault classification:

- **Synthetic Data Generation**: Using the `make_classification` function to generate synthetic fault data with adjustable parameters such as the number of features, clusters, and class separation.
- **Fault Classification on Synthetic Data**: Training models on the generated synthetic dataset to classify faults and evaluating their performance.
- **Comparison of Models**: Comparing the performance of models trained on both synthetic data and real-world data, analyzing the impact of synthetic data on fault detection.

## Data Source

The dataset for these assignments is available via the following link:

- [Fault Detection Dataset on Google Drive](https://drive.google.com/file/d/1o72UZ4KYSlT62tB7iG-AfuHoj3N2Pe8z/view?usp=sharing)

Make sure to download and use this data in the exercises.

## How to Run the Code

1. Clone this repository or download the notebook files.
2. Install the required libraries. You can install the dependencies using:

   ```bash
   pip install -r requirements.txt
