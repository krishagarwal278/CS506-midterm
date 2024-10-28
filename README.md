<h1> CS506 Kaggle Competition </h1>

<h2> Amazon Movie Review Star Rating Prediction </h2>
<h3> Project Overview </h3> 
This project aims to predict star ratings for Amazon movie reviews based on the review text and metadata. The primary objective is to build a machine learning model that can accurately classify reviews into 1-5 star ratings by extracting meaningful insights and patterns from the available data. The project avoids deep learning methods, focusing on feature engineering and traditional machine learning techniques.

<h2> <b> Goals </b> </h2>
Accurate Rating Prediction: Predict the star rating of each review using a variety of features.
Insightful Feature Engineering: Design features that capture review sentiment, user engagement, and other relevant factors to improve model accuracy.
Model Interpretability: Emphasize interpretability and simplicity, using K-Nearest Neighbors (KNN) for classification.

<h3> Methodology </h3>
<h4> Data Analysis: </h4> Initial analysis of the review dataset to understand the distribution of ratings, helpfulness metrics, review length, and other characteristics.
<h4> Feature Engineering: </h4>
Helpfulness Ratio: Ratio of helpful votes to total votes. </br>
Sentiment Features: Count of positive/negative words and text-based sentiment scores.  </br>
Review Length and Emotion: Word count, capitalization ratio, and exclamation count as indicators of review intensity.
<h3> Model Selection: </h3>
K-Nearest Neighbors (KNN) with optimized k=500 and Euclidean distance.
Tuning involved experimenting with different values for k to achieve the highest accuracy. </br>
<h3> Evaluation: </h3>
Accuracy and confusion matrix were used to evaluate model performance.
The final model achieved an accuracy of approximately 0.533, a significant improvement over the initial baseline of 0.40.
