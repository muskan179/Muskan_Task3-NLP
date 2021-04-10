# Muskan_Task3-NLP

## Objective
The task is to investigate which supervised machine learning methods are better suited to solve a supervised text classification problem.
We want to assign a product to one of 32 categories based on its description. Each new description is assigned to one and only one group, according to the classifier. This is multi-class text classification problem. The dataset can be found in this link https://docs.google.com/spreadsheets/d/1pLv0fNE4WHokpJHUIs-FTVnmI9STgog05e658qEON0I/edit?usp=sharing
and should be saved as flipkart.csv.

## Steps Involved:

* Data Exploration:
I started by looking at some example as well as the number of categories and descriptions, and making sure there were no missing or null values.
* Data Cleaning:
Correcting incorrect encodings, splitting the product category tree, and eliminating unnecessary/invalid features that have no bearing on prediction. I took out the punctuation and stopwords, tokenized it, and then lemmatized it.
* Data Preprocessing:
Converting the text features into vectors using TFIDF vectorizer, also used OneHotEncoder on product catagories and tried Google Word2Vectorizer
* Feature Engineering: 
Adding additionally created features to training and test datasets
* Model Training:
Training different classification models-Logistic Regression,(Multinomial) Naive Bayes, Linear Support Vector Machine
& Random Forest and comparing them.
* Evaluation:Comparing the accuracy and recall scores for different models to select the most suitable one. Accuracies of them are as follows:
* LinearSVC                 0.9438
* LogisticRegression        0.8850
* MultinomialNB             0.8440
* RandomForestClassifier    0.6036

## Additional information 
Comments and explanation for why the steps were added and thier need and how it works as well as all errors i faced is all documented in the added comments.
