# Disaster-Prediction-from-tweets
Predict which Tweets are about real disasters and which ones are not

Kaggle Competition: https://www.kaggle.com/c/nlp-getting-started/
Kaggle Notebook: https://www.kaggle.com/swatisk2702/disaster-prediction-using-tweets

# Competition Description:

Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies). 
But, it’s not always clear whether a person’s words are actually announcing a disaster. In this competition, we are  challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. 

# Approach:

1. Preprocess data:
  - Used Weight of Evidence(WOE) encoding to encode keywords and location.
  - Used TF-IDF vectorizer to encode tweets.
  
2. Models Used - Used an ensemble of the following models to create a two tier model:
  - Ridge Classifier
  - Support Vector Machine(SVM)
  - Decision Tree 
  - XGBoost
  
  
