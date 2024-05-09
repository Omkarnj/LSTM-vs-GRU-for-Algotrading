# LSTM-vs-GRU-for-Algotrading
The main Objective of this project was to analyze the results of both LSTM and GRU on temporal dependencies of stock price data.

## I would like to first tell you the special part about this project - its flexibility. The code used in this project can be used with ANY stock/crypto/commodities that you desire. You only need to find its name on yahoo finance and replace that name with the one I used in the code. While I cannot guarantee similar performance on other stocks, the code will indeed run without any hickeys.

## I have mainly used the closing prices of the stocks to predict their movement, in this example I used Kotak Bank historical stock price data, of which the closing prices over time are visualised below - 


![image](https://github.com/Omkarnj/LSTM-vs-GRU-for-Algotrading/assets/135634070/f25c9d9a-8390-41b9-9707-5121227ecda4)



## The data from 2023 and beyond would need to be predicted by the model, the entire train-test split is visualised below - 


![image](https://github.com/Omkarnj/LSTM-vs-GRU-for-Algotrading/assets/135634070/f2f50da5-8ea6-4550-a620-a4172db6898f)


## This is the real and predicted lines for the LSTM model on a graph - 


![image](https://github.com/Omkarnj/LSTM-vs-GRU-for-Algotrading/assets/135634070/ea78253c-452f-4038-895d-2586c5b0b521)


## The Root mean squared error is 21.28 for the LSTM model


# GRU model - 



![image](https://github.com/Omkarnj/LSTM-vs-GRU-for-Algotrading/assets/135634070/bf4d55fd-8fd1-4975-ad57-6f3bbd2a0313)



## The root mean squared error is 69.68 for the GRU model 
Risk Mitigation: The lower RMSE obtained with the LSTM model suggests that it outperforms the GRU model in terms of prediction accuracy. This insight can guide stakeholders in choosing the most effective model for stock price forecasting. By utilizing the LSTM model, investors can mitigate risks associated with inaccurate predictions and make more reliable investment decisions.
The comparison between the LSTM and GRU models highlights the importance of selecting the appropriate architecture for deep learning models in stock price prediction tasks. The superior performance of the LSTM model suggests that it may be better suited for capturing long-term dependencies and complex patterns in the data. This insight informs future model development efforts and underscores the significance of model architecture selection in achieving accurate predictions.
