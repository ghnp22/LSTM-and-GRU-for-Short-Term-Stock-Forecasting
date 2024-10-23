# LSTM and GRU for Short Term Stock Forecasting

### Description:

The stock market is a complex and volatile field, requiring accurate prediction tools to optimize profits and minimize risks. Machine learning applications, particularly LSTM and GRU, have the capability to process large datasets and recognize complex patterns, enhancing the accuracy of short-term stock price predictions. These models also improve accuracy in making investment decisions based on historical data, technical indicators, and macroeconomic factors like exchange rates.

***Research methodology***
1. Data Collection: Historical stock prices, technical indicators, and exchange rates were collected and preprocessed to remove noise and missing values.
2. Data Preprocessing: Techniques like normalization and data transformation were applied to make the model easier to train and more accurate in its predictions.
3. Model Construction: Both LSTM and GRU models were implemented, with data split using the rolling window method for training and testing.
4. Model Evaluation: The performance of the models was evaluated using metrics such as RMSE, MAE, and MAPE to compare the accuracy and stability of each model.

***Output:***
Both models demonstrated strong forecasting abilities when applied to key features. The results showed that GRU is more stable when using different data windows, with GRU's RMSE at 999.62 and LSTM's at 1287.24. The lowest MAPE reached 1.08%, proving the high accuracy of the models in predicting short-term stock prices.

### Main files:
1. [LSTM and GRU.ipynb](https://github.com/ghnp22/LSTM-and-GRU-for-Short-Term-Stock-Forecasting/blob/main/LSTM%20and%20GRU.ipynb): The code file implementing the models.
2. [Shorterm Stock Forecasting.pdf](https://github.com/ghnp22/LSTM-and-GRU-for-Short-Term-Stock-Forecasting/blob/main/Shorterm%20Stock%20Forcasting.pdf): A comprehensive project report detailing the methodology and results.
3. [all_grains_data.csv](https://github.com/ghnp22/LSTM-and-GRU-for-Short-Term-Stock-Forecasting/blob/main/all_grains_data.csv): The dataset used for training and testing the models.

### Collaborators:
This project succeeded thanks to the close collaboration of all contributors.
1. Tran Si Dan
2. Trinh Quoc Thinh
3. Duong Van Nhut Duy
4. Nguyen Thien Huy


