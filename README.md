# ML-Projects

# Machine Learning Projects

Welcome to my **Machine Learning Projects** repository! This repository contains my hands-on projects in machine learning, data analysis, and predictive modeling. Each project focuses on solving a practical problem using data-driven approaches.

## About This Repository

I created this repository to document my learning journey, practice machine learning concepts, and build practical projects using Python and its data science ecosystem.

The projects cover data preprocessing, exploratory data analysis, classification, model evaluation, and predictive analytics.

## Projects
### 1. Breast_Cancer_Wisconsin Classification
## 📌 Project Overview
This project focuses on classifying breast tumors as **Benign** or **Malignant** using machine learning algorithms and the Breast Cancer Wisconsin Diagnostic dataset. The goal is to build and compare classification models and identify the most suitable model for breast cancer diagnosis support.

## 🎯 Objectives

- Perform exploratory data analysis (EDA) on the dataset.
- Preprocess the data for machine learning.
- Train and evaluate multiple Support Vector Machine (SVM) classifiers.
- Compare Linear, Polynomial, and RBF kernels.
- Use GridSearchCV to identify the best hyperparameters.
- Evaluate model performance using appropriate classification metrics.

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin Diagnostic dataset**, available through Scikit-learn.

- **Number of samples:** 569
- **Number of features:** 30 numerical features
- **Target classes:** Benign and Malignant
- **Feature types:** Measurements derived from digitized images of fine needle aspirates (FNA) of breast masses.

The features describe characteristics of cell nuclei, such as radius, texture, perimeter, area, smoothness, and compactness.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Support Vector Machine (SVM)
- GridSearchCV

## ⚙️ Project Workflow

1. **Data Loading:** Load the Breast Cancer Wisconsin Diagnostic dataset.
2. **Exploratory Data Analysis:** Examine feature distributions, target classes, and relationships between features.
3. **Data Preprocessing:** Prepare the numerical features for model training and apply scaling where appropriate.
4. **Model Training:** Train SVM classifiers with different kernels:
   - Linear Kernel
   - Polynomial Kernel
   - RBF (Radial Basis Function) Kernel
5. **Hyperparameter Tuning:** Use GridSearchCV to search for suitable hyperparameters.
6. **Model Evaluation:** Compare model performance using classification metrics and confusion matrices.

## 📈 Evaluation Metrics

The models can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help assess classification performance, including the model's ability to identify malignant cases.

## 🔍 Key Learning Outcomes

- Understanding a binary classification problem.
- Applying SVM with different kernel functions.
- Using feature scaling in machine learning workflows.
- Performing hyperparameter tuning with GridSearchCV.
- Evaluating classification models using multiple metrics.

## ⚠️ Disclaimer

This project is for educational and research purposes only. It is not intended to replace professional medical advice, diagnosis, or clinical decision-making.

### 2. Holiday Package Purchase Prediction

**Objective:** Predict whether a customer is likely to purchase a holiday package using customer-related information and machine learning.

- **Problem Type:** Binary Classification
- **Dataset:** Travel customer dataset (`Travel.csv`)
- **Algorithm:** Random Forest Classifier
- **Tools:** Python, Pandas, NumPy, Scikit-learn, Google Colab
- **Test Accuracy:** 91.82%

**Key Features:**
- Data preprocessing and missing-value handling
- Categorical feature encoding
- Model training and evaluation
- Precision, recall, F1-score, and confusion matrix analysis
- Sample customer purchase prediction

**Key Observation:** The model achieved 91.82% test accuracy, with a recall of 62% for customers who purchased a package. Improving buyer recall is an important direction for future work.

**Project Notebook:** [Holiday Package Prediction](./Holiday-Package-Prediction/Holiday_Package_Prediction.ipynb)

## Technologies & Tools

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Google Colab
- Git and GitHub

  
### 3. Customer Review Sentiment Analysis

## Overview
An end-to-end Natural Language Processing (NLP) project that classifies IMDb movie reviews as positive or negative.

## Dataset
- **Source:** [IMDb Dataset on Hugging Face](https://huggingface.co/datasets/stanfordnlp/imdb)
- **Total reviews:** 50,000
- **Training samples:** 25,000
- **Testing samples:** 25,000
- **Classes:** Positive and Negative

## Methodology
1. Data exploration and quality checks
2. TF-IDF text feature extraction using unigrams and bigrams
3. Model comparison using Multinomial Naive Bayes, Logistic Regression, and Linear SVM
4. Hyperparameter tuning with GridSearchCV and stratified cross-validation
5. Evaluation using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix
6. Interactive prediction application using Streamlit

## Technologies
Python, Pandas, Scikit-learn, Hugging Face Datasets, Matplotlib, Seaborn, Joblib, Streamlit.

## Results
Add the actual test metrics after running the notebook. Do not insert estimated or unverified scores.

## Run the Application
Install the dependencies and run:

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Limitations
The model is trained on IMDb movie reviews. Its performance on product reviews, other domains, or other languages has not been established.

## Disclaimer
This project is for educational purposes and is not intended for high-stakes decision-making.

## Repository Structure

```text
MLprojects/
├── README.md
└── Breast_Cancer_Wisconsin_(Diagnosis)
    ├── README.md
    └── Breast_Cancer_Wisconsin_(Diagnosis).ipynb
└── Holiday-Package-Prediction/
    ├── README.md
    └── Holiday_Package_Prediction.ipynb
```

## Future Projects

More projects will be added as I continue exploring:

- Classification and regression
- Exploratory data analysis
- Feature engineering and model optimization
- Deep learning
- Real-world predictive analytics

## Goals

- Strengthen my understanding of machine learning algorithms.
- Develop practical data preprocessing and model evaluation skills.
- Build reproducible, well-documented projects.
- Apply machine learning to real-world problems.

---

**Thank you for visiting my repository!**

