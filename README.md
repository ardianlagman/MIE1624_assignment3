# MIE1624_assignment3
Perform data cleaning and preparation to compare sentiment analysis between general tweets and 2021 Canadian election tweets

Prepared data using Bag-of-Words and TF-IDF methods for models. ML models used were LogisticRegression, KNN, Naive-Bayes, Random Forest, Decision Tree, XGB, and Support Vector Machines.

Data was cleaned to replace HTML links, to lower case, to remove stopwords, to remove URLs. Lemmatization was also used. 

Discrepancies were found in the performance of the model chosen between the general sentiment and the elections dataset. For example, logistic regression achieved 0.971 accuracy, 0.979 F1 score, and 0.967 AUC score on the general sentiment data. However, on the elections data, the model achieved 0.703 accuracy, 0.709 F1 score, and 0.736 AUC score. 
