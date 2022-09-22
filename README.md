# ML-Crypto-Currency-Prediction-Project

The crypto currency prediction project is based on the idea of algorithmic treading leveraging Machine Learning. The main objective of the project is to predict the probability of stop loss and take profit in next 'n' hours and base our buy/sell strategy based on the model predictions. 

The data for the project was collected on 15 cryptocurrencies for a time period of over an year via Binance API calls in Python. The data wrangling, feature engineering, feature selection, model development, evaluation and selction was all done in Python using different packages such as Pandas, Matplotlib, Scikitlearn and Keras. I wrote a custom function that helped in assigning labels of stop loss and take profit in the next 'n' hours window. 

XGBoost and Neural Networks were the two ML techniques used to model the probability of stop loss and take profit. A final XGBoost model with an AUC of 90% on train data and 88% on test data was selected using Grid Search and the model was interpreted using SHAP analysis. 

In this repository, I have included the code files for Data Processing and Feature Engineering and Model Building and Evaluation. The code has comments that will guide you on what each step is supposed to do. 

Feel free to give your feedback or let me know if you have any questions!
