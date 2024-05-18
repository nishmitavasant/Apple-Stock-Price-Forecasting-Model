# Apple Stock Price Forecasting Model

## Project Overview
This project aims to enhance the accuracy of forecasting Apple's stock price by leveraging advanced statistical analysis and machine learning techniques. We used a range of methods including logistic regression, random forests, and LSTM neural networks to predict stock price movements based on historical data. The data was sourced from an API and preprocessed to fit the model requirements.

## Data Loading and Preprocessing
The data, initially stored in a single large file, was separated into four CSV files due to GitHub's file size restrictions. These files are then combined into a single DataFrame for analysis.


## Key Steps in Analysis

### Data Cleansing
- Handle missing values and drop unnecessary columns to streamline the dataset.

### Feature Engineering
- Extract relevant features like the hour from timestamps and apply transformations such as one-hot encoding on categorical data.

### Exploratory Data Analysis
- Perform statistical analysis on features like RSI (Relative Strength Index) and MACD (Moving Average Convergence Divergence) to understand their impact on stock prices.

### Model Building
- Develop various models including logistic regression, random forests, and LSTM (Long Short-Term Memory networks) to forecast stock price movements.

## Repository Contents
- [`AAPL.ipynb`](https://github.com/yourgithubusername/Apple-Stock-Price-Forecasting-Model/blob/main/AAPL.ipynb): Jupyter notebook containing the detailed analysis and model development.
- `data/`: Directory containing the datasets used in the analysis, split into multiple CSV files due to size constraints.

## Technologies Used
- **Python Libraries:** Pandas, NumPy, TensorFlow, Matplotlib, Seaborn
- **Machine Learning Techniques:** Logistic Regression, Random Forest, LSTM

## How to Run
1. Clone the repository.
2. Install the necessary Python packages:
   ```bash
   pip install pandas numpy tensorflow matplotlib seaborn
3. Run the notebook AAPL.ipynb using Jupyter Notebook or Google Colab to view the analysis and models.

