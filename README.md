# AIML_2_SpamClassifier_BYTE
Machine learning project to classify SMS messages as spam or genuine.
# Spam SMS/Email Classifier

## Project Overview

This project uses machine learning to classify text messages as **Spam** or **Not Spam**.

## Objective

To identify potentially unwanted messages using natural language processing and machine learning.

## Dataset

UCI SMS Spam Collection.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* TF-IDF Vectorization
* Multinomial Naive Bayes
* Matplotlib

## Methodology

1. Load and inspect the dataset.
2. Convert text messages into numerical features using TF-IDF.
3. Split the data into training and testing sets.
4. Train a Multinomial Naive Bayes classifier.
5. Evaluate the model using accuracy, precision, recall, F1-score and a confusion matrix.
6. Test sample messages and display prediction confidence.

## Project Files

* `spam_classifier.pkl` — saved machine learning model.
* `confusion_matrix.png` — confusion matrix visualization.
* `.ipynb` notebook — code, training and evaluation.

## How to Use

Open the notebook in Google Colab or Jupyter Notebook and run the cells in order. The saved model can be loaded using Joblib.

## Conclusion

This project demonstrates a basic machine learning approach to text message spam classification.

**Note:** Refer to the notebook for the actual evaluation results and implementation details.
