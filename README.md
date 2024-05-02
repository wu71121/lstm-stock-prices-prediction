# lstm-stock-prices-prediction
An LSTM Model for Detecting Recessions

1. DESCRIPTION:
CODE.ipynb to get the stock price data using Yahoo API, model, and visualize the stock price prediction using LSTM. 

2. EXECUTION

*optional* Step 1 [data collection]: To collect data, run "Data Cleaning and Scraping" section in CODE.ipynb. Two csv files (testing_filtered.csv, training_filtered.csv) should be generated.

*optional* Step 2 [data wrangling]: run "Data Cleaning and Scraping" section in CODE.ipynb. Or if Step 1 was not run, skip this step and use the dataset we provide.

*optional* Step 3 [data cleaning]: Run the ~Data Preprocessing~ section and ~Store data in ready to use format~ section in CODE.ipynb. This should generate a numpy file train_data_array.npy under ./CODE/Data

*optional* Step 4 [training the neural model]: Run the ~Model Training & Evaluation~ section in CODE.ipynb. This should train the neural model and store its weights in LSTM_with_attention_batch_3000.pth under ./CODE/Data/

Step 5 [Evaluation]: Run the ~Evaluation~ section in CODE.ipynb.

Step 6 [Visualization]
