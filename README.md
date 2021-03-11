# Machine Learning Project: Utilizing Stock Signals to Predict Future Price
Utilizing Alpaca's API to pull in daily closing price data of the S&P500, we developed a machine learning model consisting of five features to determine the model's ability of achieving the target of producing positive returns.


## Data Sets, Packages/Libraries and Visualization:
1. https://app.alpaca.markets/paper/dashboard/overview - 3yrs of Stock Data consisting of last trade, last quote, 1-30min, 1-4hrs, daily, weekly and monthly bar data.
2. Sklearn ensemble Random Forest Classifier, make_classification dataset, confusion matrix, accuracy score, classification report, train_test_split and Standard Scaler, Pathlib, Pandas, Numpy, Joblib, TensorFlow.


### Key Questions:
1. How much of an impact does leading and/or lagging indicators have on stock returns?
2. Can the modeled data effectively improve accuracy over time given enough pricing data?
3. Can the modeled data effectively minimize losses over time with additional features?
4. Are there features that could be applied to depressed stocks which would produced positive returns?
5. What impact would the model have on stocks with low volatility?


### Methods used in the Machine Learning Project:
- Assign Training and testing windows
- Split x & y training dataset
- Setup Neural Network using Sklearn pre-processing, model_selection & TensorFlow using keras layers and models
- Standard Scaler
- Compile the model
- fit the training data set
- Generate accuracy and loss metrics


![](https://github.com/lchristij/MLProject/blob/main/images/accuracy.png)
Accuracy Plot:

![](https://github.com/lchristij/MLProject/blob/main/images/loss.png)
![](https://github.com/lchristij/MLProject/blob/main/images/metrics.png)
Loss Plot:


![](https://github.com/lchristij/MLProject/blob/main/images/returns.png)
Returns:
