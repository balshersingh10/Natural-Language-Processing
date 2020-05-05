![Natural Language Processing](https://miro.medium.com/max/1200/1*LSuNzztxNawWKe4LmGrUjA.jpeg)
# Sentiment Analysis on Movie Reviews [Natural Language Processing (NLP)]
Sentiment Analysis means analyzing the sentiment of a given text or document and categorizing the text/document into a specific class or category (like positive and negative). In other words, we can say that sentiment analysis classifies any particular text or document as positive or negative. Basically, the classification is done for two classes: positive and negative.

Sentiment Analysis is also referred as Opinion Mining. It’s mostly used in social media and customer reviews data.

In this repo, we will learn about labeling data, extracting features, training classifier, and testing the accuracy of the classifier.

## WE ALSO INTRODUCED NATURAL LANGUAGE PROCESSING IN THIS REPO SUCH AS :
* Tokenizing words [word_tokenize()]
* Tokenizing sentences [sent_tokenize()]
* Discovering stop words [set(stopwords.words('english'))]
* Stemming Words [PorterStemmer()]
* Speech Tagging with NLTK
* Unsupervised sentence tokenizer [PunktSentenceTokenizer]
* Chunking
* Chinking
* Named Entity Recognition with binary=True
* Named Entity Recognition with binary=False
### A. Feature Selection
Feature selection is finding the subset of original features by different approaches based on the information they provide, accuracy, prediction errors.
The features used in the project are:
- First 4000 most common frequently used words imported from nltk.corpus --> movie_reviews.words()
### B. Model Selection
* KNN model with nearest neighbours set eqaul to 2
* Decision Tree
* Random Forest
* Neural Net
* AdaBoost
* SVC/SVM model with Linear kernel
* SVC/SVM model with RBF kernel
* SVC/SVM model with Sigmoid kernel
* SVC/SVM model with Polynomial kernel
### C. Training the models with Data
The data taken is from **NLTK library (from nltk.corpus import movie_reviews)**
### D. Taining Data and Testing Data
75% of above data is training and 25% is testing data.
#### Then the Class is predicted:
- Positive
- Negative
## Result =>
Accuracy on Test Set is:
* Nearest Neighbors: 52.800000000000004 %
* Decision Tree: 61.199999999999996 %
* Random Forest: 52.400000000000006 %
* Neural Net: 81.2 %
* AdaBoost: 79.0 %
* SVM Linear: 80.2 %
* SVM RBF: 84.2 % [HIGHEST ACCURACY]
* SVM Sigmoid: 82.39999999999999 %
* SVM Polynomial: 84.2 % [HIGHEST ACCURACY]

### Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**
