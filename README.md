## README.md
# Stock_Prediction_Using_Random_Forest
This repository contains Python code for predicting stock price movements using machine learning techniques. The provided code utilizes historical data of the S&P 500 index (^GSPC) obtained from Yahoo Finance, and employs a Random Forest Classifier for prediction.

### Contents

- `stock_prediction.ipynb`: Jupyter notebook containing the Python code for predicting stock price movements.
- `README.md`: This file providing an overview of the project and instructions for running the code.

### Dependencies

- Python 3.x
- Libraries: `yfinance`, `pandas`, `sklearn`, `matplotlib`

### Usage

1. Ensure you have Python installed on your system along with the required dependencies.
2. Clone this repository to your local machine:

    ```
    git clone https://github.com/your-username/stock-prediction.git
    ```

3. Navigate to the cloned directory:

    ```
    cd stock-prediction
    ```

4. Open `stock_prediction.ipynb` in Jupyter notebook or any compatible environment.
5. Execute the code cells in the notebook sequentially.
6. The notebook provides functions for backtesting the model, adjusting parameters, and making predictions.

### Description

- The notebook `stock_prediction.ipynb` demonstrates the process of predicting stock price movements of the S&P 500 index using a Random Forest Classifier.
- It fetches historical data from Yahoo Finance, preprocesses the data, and constructs features for prediction.
- The Random Forest Classifier is trained on the data and used to make predictions.
- The notebook provides functions for backtesting the model on historical data and evaluating its performance using precision scores.
- Additionally, it includes features for adjusting parameters such as the number of estimators and minimum samples split, as well as for incorporating rolling averages and trends for improved prediction accuracy.

### Contributors

- [Himaanshu Sharma][(https://github.com/Himaan1502)]
