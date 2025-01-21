# Sarcasm_detection
## Overview
Sarcasm detection is a critical component of modern sentiment analysis, particularly for understanding user-generated text on platforms like Twitter and Reddit. This project explores the complexities of sarcasm classification and provides a comprehensive evaluation of various machine learning models, including:

- Logistic Regression
- Random Forest
- SVM
- Transformer-based models (DistilBERT)
  
Our study utilizes a dataset of Reddit comments sourced from Kaggle, supplemented with Twitter data, to evaluate the performance and adaptability of these methods across platforms with distinct linguistic features and constraints.

## Key Findings
- Baseline Models: Logistic Regression and Random Forest achieved modest accuracy and F1 scores but struggled to capture the subtleties inherent in sarcastic content.
- Improved Performance: SVM yielded better-balanced precision and recall metrics, showcasing its ability to manage nuanced sarcasm detection.
- Transformer-Based Approach: DistilBERT significantly outperformed other methods, achieving:
   - 76% accuracy on Reddit data.
   - 77% accuracy on Twitter data. These results were obtained using only half of the available dataset, emphasizing the robustness of transformer-based methods.

## Project Objectives
With this project, we wanted to compare traditional machine learning methods with advanced deep learning techniques and highlight the challenges of sarcasm detection and propose directions for future work.

## Dataset
The project employs a combined dataset:
- Reddit comments: https://www.kaggle.com/datasets/danofer/sarcasm
- Twitter data: https://www.kaggle.com/datasets/nikhiljohnk/tweets-with-sarcasm-and-irony?select=train.csv

For a detailed explanation of methodologies, results, and insights, refer to the project report available in this repository.
