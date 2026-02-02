# AI-ML-Tasks
# Task - 1
## Iris Flower Classification

**Classify iris flowers into three species (Setosa, Versicolor, Virginica) based on petal and sepal measurements.**

### Overview
This project uses the classic Iris dataset to build and evaluate machine learning classifiers. The goal is to predict the species of an iris flower from its features.

### Features
- Data exploration with visualizations (scatter plots, histograms)  
- Training of multiple classifiers: Logistic Regression, K-Nearest Neighbors, Decision Tree  
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix  
- Insights on feature importance and class separability  

### Results
- All models achieved **100% accuracy** on the test set  
- Precision, recall, and F1-score: **1.00 for all classes**  
- Confusion matrix shows no misclassifications  
- Petal features provide clear decision boundaries  
- Default hyperparameters are sufficient for this dataset  

# Task - 2
## Spam Mail Detector 📧

Detect spam emails using **Machine Learning** and **Natural Language Processing (NLP)**.

### Overview
This project builds a classifier to distinguish between **spam** and **ham** (non-spam) emails using the **Enron Email Dataset**. The workflow includes:  

- Text preprocessing: lowercasing, stopword removal, tokenization  
- Feature extraction with **TF-IDF**  
- Classification using **Naive Bayes**  
- Model evaluation using **Accuracy, Precision, Recall, F1-score**  

The trained model can also be tested on new emails for real-world validation.

### Features
- High accuracy spam detection (~98%)  
- Handles unseen emails with probability-based prediction  
- Easy-to-use pipeline for preprocessing, training, and testing  

### Tech Stack
- Python 3  
- pandas, nltk, scikit-learn  



