# Text-Classification
This is a text classification project using three different classifiers (SVM, Naïve Bayes and simple Logistic Regression) to predict the gender and the speaker of a soap opera from the script’s lines. 
The dataset was pre-processed (stopword and punctuation removal, lemmatization, tokenization), using pandas and nltk, 
and for the feature selection a bag of words model was created as long as a TF-IDF method. 
To evaluate the classifiers, the below metrics were used: Accuracy, Precision, Recall and F-Score.
