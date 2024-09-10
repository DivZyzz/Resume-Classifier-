# Resume-Classifier-
Classify text documents as resumes or non-resumes using machine learning. The project includes data loading, text preprocessing, TF-IDF feature extraction, and Logistic Regression model training. Achieved high accuracy and evaluated with metrics like accuracy, AUC, and confusion matrix

**Project Overview**

In this project, I aimed to build a model to differentiate between resumes and other types of documents. I followed these key steps:

**Data Loading and Exploration:** I loaded the dataset from a CSV file and explored it to understand its structure.

**Text Preprocessing:** I cleaned the text data by converting it to lowercase, removing non-alphanumeric characters, tokenizing, removing stop words, and lemmatizing.

**Feature Extraction:** I used TF-IDF to convert the text into numerical features, including bigrams to capture word patterns.

**Model Building:** I trained a Logistic Regression model and fine-tuned it using cross-validation and GridSearchCV.

**Model Evaluation:** I evaluated the model’s performance using accuracy, confusion matrix, and ROC curve with AUC scores.

**Feature Importance:** I analyzed the importance of different features to understand which words most influenced the classification.

**Accuracy:** The logistic regression model achieved an accuracy of 98.96%.

**AUC:** The AUC score for multiclass classification using the 'ovr' strategy was 0.99977.

**Most Important Features:** The words contributing the most to the classification were
['cases' 'com' 'maharashtra' 'details' 'board' 'accounts' 'january' 'university' 'mumbai'
‘legal']
