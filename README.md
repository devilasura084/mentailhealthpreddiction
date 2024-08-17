# Sentiment Analysis with Random Forest Classifier

This project performs sentiment analysis on a dataset using a Random Forest Classifier. The analysis is performed after vectorizing text data with TF-IDF and balancing the dataset using SMOTE to address class imbalance.

## Project Overview

The project aims to classify text statements into different sentiment categories using a machine learning approach. A Random Forest Classifier is trained on the TF-IDF vectorized text data, and the performance of the model is evaluated using a test dataset.

### Steps Involved:

1. **Data Loading and Preprocessing**:
   - The dataset is loaded using pandas, and any missing data is dropped.
2. **Train-Test Split**:
   - The data is split into training and testing sets with an 80-20 split ratio.
3. **TF-IDF Vectorization**:
   - Text data is transformed into TF-IDF features with a maximum of 5000 features.
4. **Balancing the Dataset**:
   - SMOTE (Synthetic Minority Over-sampling Technique) is applied to handle class imbalance in the training dataset.
5. **Model Training**:
   - A Random Forest Classifier is trained on the resampled training dataset.
6. **Model Evaluation**:
   - The model is evaluated using the test dataset, and the classification report is generated.
7. **Prediction on New Data**:
   - Predictions are made on new text data, and the results are displayed.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
