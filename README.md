# Predicting_Stock_Prices

This project aims to predict stock prices using Scikit-learn library and plotting a graph using Matplotlib.
We create three models for this using SVR(Support Vector Regression) from sklearn(since support vector machine can be used in classification as well a regression).
The three models are linear, polynomial and rbf(radio basis function) and then predict which model gives the best result.

### Code and Resources Used

 **Language:** Python 3.8
 
 **Libraries and Modules:** Numpy, Matplotlib, Keras, scikit-learn, pandas 
 
 **Dataset:** Last 3 months Data from [NASDAQ](https://www.nasdaq.com/)
 
 **Keywords:** Classification, tpot, radiation, machine learning 
 
 **Step 1:** Get Data from NASDAQ on the choice of company and return Pandas framework.
 
 **Step 2:** Load the data into sequence with the seq length.

 **Step 3:** Build a 2 stacked LSTM with 2 FCL with Keras, and return a Keras.Sequential.
 
 **Step 4:** Train the model and tune hyperparameters.
 
 **Step 5:** Test the model.
 
 **Step 6:** Plot the graph of growth using Matplotlib.
 
 **Note:** This is an updated version of preferred procedure of the pervious code.
 
 **Results**
 
 ![plot](https://github.com/ShrishtiHore/Predicting_Stock_Prices/blob/master/stock_price_prediction_output.png)
 
 **References**
1. https://github.com/elliottlin/Predict_stock_price_LSTM
