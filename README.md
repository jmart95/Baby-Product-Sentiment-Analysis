# Amazon Baby Product Sentiment Analysis
## Context
Sentiment analysis is a crucial topic in the field of NLP; it has easily become one of the more relevant topics in the field because of  the number of business problems it is solving. One such business problem involves understanding customer reviews which can excerbated to add insight in business decision making. 
## Dataset
Amazon Baby Product Reviews Dataset from Kaggle Competition (https://www.kaggle.com/sameersmahajan/reviews-of-amazon-baby-products)
## Objective
Compare and evaluate different models for Sentiment Analysis. Project includes using both the Count and TfIdf Vectorizers for text fitting.
## Steps
1. Import key packages such as NLTK and sklearn's Count and TfIdf Vectorizers
2. Load and preprocess the Baby Product Review dataset 
    * Make sure to scale sentiment values
3. Prepare Count Vectorizer
    * Fit Count Vectorizer
    * Evaluate Logistic Regression, SVM, and K-Nearest Neighbors models
4. Prepare TfIdf Vectorizer
    * Fit TfIdf Vectorizer
    * Evaluate Logistic Regression, SVM, and K-Nearest Neighbors models
## Results
* TF-IDF vectorizer performed slightly better than the count vectorizer part. 
* Logistic regression was the best out of all three classifiers across all performance metrics.
* Although true positive rates look very good for the KNN Classifer, its true negative rates look really poor.
## References
* https://towardsdatascience.com/tf-idf-simplified-aba19d5f5530
* https://www.nltk.org/