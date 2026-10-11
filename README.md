### Fake News Detection using Machine Learning & Explainable AI (LIME)

This repository contains an end-to-end Machine Learning pipeline designed to classify news articles as **Real** or **Fake**, complete with **Explainable AI (LIME)** to interpret individual model predictions.

## 📁 Dataset Note
Due to file size limits on GitHub, the source datasets (`Fake.csv` and `True.csv`) are not included in this repository. 
* You can download the complete dataset from Kaggle: [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
* Place both CSV files in your project root directory before running the notebook.

## 🛠️ Tech Stack & Libraries
* **Data Handling & Visualization:** `Pandas`, `Numpy`, `Matplotlib`, `Seaborn`
* **Natural Language Processing (NLP):** `NLTK` (Stopwords, Lemmatization), `TF-IDF Vectorizer`
* **Machine Learning Models:** `Logistic Regression`, `Multinomial Naive Bayes`, `Support Vector Machine (LinearSVC)`
* **Explainable AI:** `LIME (LimeTextExplainer)`

## 📊 Notebook Sections Overview
1. **Introduction & Imports:** Loading all required libraries and configurations.
2. **Data Loading:** Importing `Fake.csv` and `True.csv` and merging/labeling them.
3. **Exploratory Data Analysis (EDA):** Checking dataset balance, missing values, and article length distributions.
4. **Data Preprocessing & Cleaning:** Lowercasing text, removing punctuation, handling stop words, and tokenization.
5. **Feature Engineering:** Converting text corpus into numerical vectors using TF-IDF.
6. **Data Splitting:** Partitioning data into training and testing subsets.
7. **Model Training:** Training baseline classifiers including Naive Bayes, Logistic Regression, and Support Vector Machines.
8. **Model Evaluation:** Assessing performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices
9. **Explainable AI with LIME:** Utilizing LIME to generate local feature-weight explanations for individual predictions.

## 👩‍💻 Author
Minahil Fatima

BS Computer Science Student | AI & Machine Learning Enthusiast
