Fake News Detection - README
Project Overview
This project is a comprehensive approach to detecting fake news using various Natural Language Processing (NLP) techniques and Machine Learning models. The project is structured into three main tasks:

Task 1 - Data Exploration and Preprocessing:

Loading and inspecting the dataset.
Cleaning and preprocessing text data.
Visualizing the most common words in fake and true news articles.
Task 2 - Building Machine Learning Models:

Implementing and evaluating Naive Bayes, Random Forest, and Decision Tree models using Bag-of-Words (BoW) and TF-IDF vectorization techniques.
Task 3 - Enhanced NLP Features:

Enhancing feature engineering by focusing on specific parts of speech like nouns and adjectives.
Re-training the models using the refined features.
Project Structure
fake.csv and true.csv: Datasets containing fake and true news articles.
main_code.py: Contains all the code for data preprocessing, feature extraction, and model training.
README.md: This file, providing an overview of the project and instructions for running the code.
Getting Started
Prerequisites
Make sure you have the following libraries installed:

bash
Copy code
pip install pandas numpy nltk matplotlib seaborn scikit-learn wordcloud
Data
Ensure the fake and true news datasets are located in the same directory as your code. Update the paths in the code to reflect their location on your system.

Running the Code
Data Exploration and Preprocessing:

Load the datasets and inspect the initial few rows.
Apply preprocessing steps like tokenization, stopwords removal, lemmatization, and stemming.
Visualize the top 100 words in fake and true news articles.
Building Machine Learning Models:

Combine and shuffle the datasets.
Apply Bag-of-Words and TF-IDF vectorization techniques.
Train and evaluate Naive Bayes, Random Forest, and Decision Tree models.
Enhanced NLP Features:

Focus on specific parts of speech, such as nouns and adjectives.
Re-train the models using these refined features and evaluate their performance.
Evaluation
After running the code, you will obtain:

Accuracy scores for each model using both BoW and TF-IDF techniques.
Confusion matrices and classification reports, providing insights into the model performance.
Results
The results of the models trained on different features and vectorization methods are printed directly in the console. You can analyze these to understand the strengths and weaknesses of each approach.

Acknowledgments
This project was completed as part of a Natural Language Processing (NLP) course project, leveraging publicly available datasets and common machine learning techniques.
