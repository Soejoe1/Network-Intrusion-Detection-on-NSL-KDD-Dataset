# Evaluating Machine Learning Algorithms for Network Intrusion Detection on NSL-KDD Dataset

This repository contains the code and resources for investigating the efficacy of three machine learning algorithms—k-Nearest Neighbors (kNN), Decision Tree, and Logistic Regression—in classifying network traffic into normal and anomalous categories using the NSL-KDD dataset.

## Project Overview

Network security is a critical aspect of modern IT infrastructure. Detecting and mitigating network intrusions is essential for maintaining data integrity and confidentiality. This project aims to identify the most effective machine learning algorithm for network intrusion detection based on various performance metrics.

## Dataset

- **NSL-KDD Dataset**: A refined version of the KDD'99 dataset, it contains over 1.5 lakh records. Each record represents a connection, characterized by 41 features, and labeled as either normal or one of four types of attacks: DoS (Denial of Service), U2R (User to Root), R2L (Remote to Local), and Probe.

## Methodology

1. **Data Preprocessing**: 
    - Data cleaning and normalization.
    - Feature selection and transformation.
    - Splitting the dataset into training and testing sets.

2. **Algorithm Implementation**:
    - Implemented k-Nearest Neighbors (kNN), Decision Tree, and Logistic Regression algorithms.
    - Trained the models on the training set.

3. **Evaluation Metrics**:
    - Accuracy
    - Precision
    - Recall
    - F1-score

4. **Performance Evaluation**:
    - Utilized confusion matrix visualization to evaluate the performance of each algorithm.
    - Analyzed the ability of each model to correctly classify different types of attacks.

## Results

- **Decision Tree**:
    - Achieved a maximum accuracy of 99%.
    - Excelled in detecting various attack types with high precision and recall.

- **k-Nearest Neighbors (kNN)**:
    - Achieved an accuracy of 98.2%.
    - Performed well in terms of precision and recall but slightly lower than Decision Tree.

- **Logistic Regression**:
    - Achieved an accuracy of 93.8%.
    - Provided reasonable results but lagged behind the other two algorithms in performance metrics.

## Insights

- The Decision Tree algorithm proved to be the most effective for network intrusion detection in this study.
- Comprehensive visualizations and detailed reports were generated to inform stakeholders about the optimal network security measures.

## Repository Structure

- `data/`: Contains the NSL-KDD dataset.
- `notebooks/`: Jupyter notebooks with step-by-step code and explanations.
- `README.md`: Project overview and setup instructions.

## Conclusion

This project provides a thorough comparison of popular machine learning algorithms for network intrusion detection, offering valuable insights and practical recommendations for enhancing network security.
