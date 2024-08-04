# Water Infrastructure Stock Prediction Using LSTM
## Overview

This project utilizes the Yahoo Finance API to fetch historical stock data for water infrastructure companies and applies Long Short-Term Memory (LSTM) neural networks for predictive analysis. The goal is to forecast the future stock prices of these companies and compare their performance over time.

## Features

* Fetch historical stock data using Yahoo Finance API
* Preprocess and prepare data for analysis
* Implement LSTM neural network for stock price prediction
* Compare predicted stock prices of individual water infrastructure companies
* Visualize predictions and performance metrics

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)
* An internet connection for fetching data from Yahoo Finance

## Installation

1. Clone the repository:
   
           git clone https://github.com/yourusername/Stock_picker-prediction_analysis.git

3. Navigate to the project directory:
   
           cd Stock_picker-prediction_analysis

4. Create a virtual environment (optional but recommended):
   
           python -m venv venv

6. Activate the virtual environment:

* Windows:
  
        venv\Scripts\activate

* MacOS/Linux:
  
        source venv/bin/activate

5. Install the required packages:

        pip install -r requirements.txt


## Results

* Data Visualization: Graphs comparing predicted vs. actual stock prices.
* Performance Metrics: Evaluation metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

* Yahoo Finance API for providing stock data.
* TensorFlow for LSTM implementation.
* Pandas and NumPy for data manipulation.
* Mathplotlib for data visualization.
