# Project 3 - DSI Reddit NLP Projecrt

# Problem Statement:
## How well can we build an NLP model based on
## data pulled from r/democrats and r/Politics
## that allows us to tell which subreddit a 
## particular submission came from.

### Contents:
- Exploratory Data Analysis
- Data Visualization
- NLP Models and Results
- Conclusions and Recommendations


### Dictionary defining terms in the DataFrames:

|Feature|Type|Description|
|---|---|---|
|Submission Title|string|Unmodified Submission Title|
|Submission Author|string|Submission Author|
|Subreddit|string|r/ Politics or r/Democrats|
|Number of Comments|int|# of Comments|
|Time Filter|string|How Many Reddit Comments to Pull|
|cleaned_submissions|string|Tokenized Submission Title|
|lemmed|string|Lemmatized Submission Title|

### Data:

[Reddit: r/Democrats: ](https://www.reddit.com/r/democrats/)
[Reddit: r/Politics: ](https://www.reddit.com/r/politics/)


### Conclusions:

The best model created, with metrics

TfidfVectorizer & LogisticRegression 

Best Score: 0.7865422951261061 

X_train, y_train Score: 0.8103670315518352
X_test, y_test Score: 0.7764705882352941 

True Positives: 1125, True Negatives: 63, False Positives: 302, False Negatives: 40 

              precision    recall  f1-score   support

           0       0.61      0.17      0.27       365
           1       0.79      0.97      0.87      1165

    accuracy                           0.78      1530
   macro avg       0.70      0.57      0.57      1530
weighted avg       0.75      0.78      0.73      1530


