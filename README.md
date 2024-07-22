# Credit-Card-Fraud-Detection

# Mitigating Bias in AI-Based Fraud Detection

## Problem Statement
The goal of this project is to develop an AI-based credit card fraud detection system that is ethical and unbiased. We aim to identify and mitigate biases in the data and models, ensure transparency in decision-making processes, and implement robust privacy measures to protect user data. Ultimately, our objective is to create a system that is fair, transparent, and respects user privacy while maintaining high accuracy in detecting fraudulent transactions.

## Introduction
In this project, we will explore various predictive models to evaluate their accuracy in distinguishing between normal transactions and fraudulent ones. Although the dataset's features are scaled and anonymized for privacy reasons, we can still perform meaningful analyses of its key aspects. Let's dive in!

## Dataset
https://drive.google.com/file/d/19FqoXdVcfHXoTpXNn0bEM9OXvV1oRBNX/view?usp=drive_link

## Outline

### I. Initial Data Insights
- **Get a Basic Understanding of the Data**  
  Explore the dataset to understand its structure, features, and the distribution of transactions.

### II. Preprocessing
- **[Scaling and Distributing](#scaling-and-distributing)**  
  Normalize and scale features to ensure consistency in the data.
- **[Splitting the Data](#splitting-the-data)**  
  Divide the dataset into training and testing sets to evaluate model performance.

### III. Mitigating Bias [Random UnderSampling and Oversampling]
- **[Distributing and Correlating](#distributing-and-correlating)**  
  Analyze class distribution and feature correlations to identify potential biases.
- **[Anomaly Detection](#anomaly-detection)**  
  Detect and address anomalies within the data that may impact model performance.
- **[Dimensionality Reduction and Clustering (t-SNE)](#dimensionality-reduction-and-clustering-tsne)**  
  Reduce dimensionality and cluster data to visualize patterns and separations.
- **[Classifiers](#classifiers)**  
  Train and evaluate various classifiers to identify the best-performing model.
- **[A Deeper Look into Logistic Regression](#a-deeper-look-into-logistic-regression)**  
  Analyze logistic regression in detail, focusing on its precision and recall.
- **[Oversampling with SMOTE](#oversampling-with-smote)**  
  Apply SMOTE to balance class distribution and improve model performance.

### IV. Testing
- **[Testing with Logistic Regression](#testing-with-logistic-regression)**  
  Evaluate logistic regression models and compare results.
- **[Neural Networks Testing (Undersampling vs Oversampling)](#neural-networks-testing-undersampling-vs-oversampling)**  
  Compare the performance of neural networks on undersampled versus oversampled datasets.

## Getting Started

### Prerequisites
- Python 3.x
- Required libraries: numpy, pandas, scikit-learn, imbalanced-learn, matplotlib, seaborn

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/preethambingi/Credit-Card-Fraud-Detection.git
   ```
2. Navigate to the project directory:
   ```
   cd Credit-Card-Fraud-Detection
   ```
3. Install the necessary packages:
   ```
   pip install -r requirements.txt
   ```

### Usage
1. Load the dataset and preprocess the data as described in the preprocessing section.
2. Apply bias mitigation techniques such as random under-sampling, oversampling, and SMOTE.
3. Train and test various classifiers, including logistic regression and neural networks.
4. Evaluate and visualize results to assess model performance and fairness.
