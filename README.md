### [Deep-Stock-Price-Prediction](https://github.com/amousavi9/Deep-Stock-Price-Prediction) presents efficient AI-based approaches for stock price forecasting

# Results
[stock_price_direction_prediction.ipynb](https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/stock_price_direction_prediction.ipynb) use an empirical mode decomposition (EMD)-based deep learning approach to predict price direction.
The model is evaluated, reporting the classification accuracy on the test set of about 85%.

<img src="https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/results/trend-prediction-acc.jpg" width="600" height="350"/>
<hr style="border:2px solid gray">

[Bitcoin_twitter_sentiment_analysis.ipynb](https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/Bitcoin_twitter_sentiment_analysis.ipynb) include two basic steps, Data extraction-cleaning and building the model to predict the Stock Closing Price.
After the data preprocessing steps, the confusion matrix showed high confusion between closing price, number of tweets, likes, replies and retweets.

<img src="https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/results/sentiment-res1.png" width="600" height="320"/> 
<hr style="border:2px solid gray">

[stock_price_prediction_using_darts.ipynb](https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/stock_price_prediction_using_darts.ipynb) use the TFT Darts model to predict price.
The TFT offers a neural network architecture that integrates the mechanisms of several other neural architectures, for instance LSTM layers and the attention heads used in Transformers.
The image below shows the evaluation of the model on the test data.

<img src="https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/results/darts-res.jpg" width="600" height="320"/>
<hr style="border:2px solid gray">
  
[SVM_RandomForest_DecisionTree.ipynb](https://github.com/amousavi9/Deep-Stock-Price-Prediction/blob/main/SVM_RandomForest_DecisionTree.ipynb) use SVM, Random Forest, and Decision Tree to predict price returns direction.
For each of these models, the classification accuracy in the test set was about 74%, 72%, and 65%, respectively.
