# Detecting-Malicious-URL-ML-project
This repository contains file related to a machine learning project. It was created during college summer training in 2022. 
The goal of this project is to detect malicious URL and classify them as good or bad mainly using Logistic Regression Algorithm and MultinomialNB.
Tthe dataset used had around 420464 rows. The training set was 80% and testing set contained 20% of overall dataset.
I compared 4 types of algorithms with two types of tokenizers viz. are tfiDFvectorizer and CountVectorizer. Firstly I compared the MultinomialNB with tfIDFvectorizer which gave accuracy of around 98.05. Then I applied MultinomialNB with CountVectorizer on the same database and got a slightly less accuracy of 97.70. After that I changed the algorithm to Logistic Regression applied with tfiDFvectorizer and got accuracy of 96.34 and lastly applied Logistic Regression with CountVectorizer and accuracy was improved to 97.23. 
So comparing all these I got to know that MultinomialNB when applied with tfIDFvectorizer and hyperparameter alpha updated to 0.1 gave me the best accuracy of 98.05.
I developed this project along with my partner Sparsh Jain. 
