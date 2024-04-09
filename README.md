# Stock-pridiction

This project demonstrates how to predict stock prices using a Stacked Long Short-Term Memory (LSTM) neural network model. The code utilizes historical stock price data from a CSV file (in this case, AAPL.csv), preprocesses the data, trains the LSTM model, makes predictions, and evaluates the model's performance.

## Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn
- TensorFlow

Install the dependencies using pip:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

## Usage

1. Clone this repository or download the script `stock_prediction.py` and the CSV file `AAPL.csv`.
2. Ensure that you have the necessary Python dependencies installed.
3. Replace the placeholder values in the code with your Tiingo API key (if applicable) and adjust any other parameters as needed.
4. Run the script `stock_prediction.py`.
5. The script will train the LSTM model, make predictions, and evaluate the model's performance.
6. Results will be displayed, including the Mean Squared Error (MSE) for both training and test datasets, and visualizations of the predicted stock prices.
