---

# Stock Price Prediction and Profitability Analysis using PyTorch

This project demonstrates how to predict stock prices and determine their profitability using a neural network model implemented in PyTorch. The model is trained on historical stock price data and is used to predict future stock prices and assess profitability.

## Overview

The project uses a dataset of historical stock prices to train a neural network model to predict future prices and determine if the investment would be profitable. It involves the following steps:
1. Load and preprocess the data.
2. Build and train the neural network model using PyTorch.
3. Make predictions and visualize the results.
4. Determine profitability based on predicted stock prices.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- PyTorch

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction-pytorch.git
   ```
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib scikit-learn torch
   ```

## Usage

1. Ensure you have the dataset file `XPREP8.csv` in the same directory as the script.
2. Run the script:
   ```bash
   python stockprediction.py
   ```

## Project Structure

- `stockprediction.py`: Main script to run the stock price prediction and profitability analysis model.
- `XPREP8.csv`: Dataset file containing historical stock prices.

## Results

The script will output:
1. The Mean Squared Error (MSE) of the model's predictions.
2. Visualization of the test and train loss.
3. Profitability analysis based on the predicted stock prices (binary classification).
4. regression loss curve:

   
   ![image](https://github.com/user-attachments/assets/c70f850b-103e-4014-9302-fecf2ba3076f)
6. classification loss curve:


   ![image](https://github.com/user-attachments/assets/ab784295-f2ea-43ec-bd05-9d660217fb9b)



## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or suggestions, feel free to reach out to [Madhesh R.L.](mailto:madheshlogan@gmail.com).

---
