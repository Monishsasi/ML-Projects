
# Gold Price Prediction

## Project Overview
Developed a **Random Forest Regressor** to forecast gold prices based on financial and time-series data.

## Features
- Feature Engineering from financial data
- Model Training and Evaluation
- Time-based data analysis

## Tools & Technologies
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Results
- Achieved a high R² score of **0.99**, indicating near-perfect predictions.

## Usage
1. Preprocess and engineer features from financial datasets.
2. Train the Random Forest model.
3. Predict gold prices.
4. Visualize trends and predictions.


## Dataset Description
The Gold Price Prediction Dataset contains 2290 records with financial and economic indicators used to predict the price of gold.

### Featur Description:

Date - Date of the record (format: YYYY-MM-DD).
SPX - Standard & Poor's 500 Index value — represents the US stock market performance.
GLD - SPDR Gold Shares ETF price — reflects the gold price movement.
USO - United States Oil Fund price — represents oil price fluctuations.
SLV - iShares Silver Trust price — reflects the price of silver.
EUR/USD - Exchange rate of Euro to US Dollar — represents the forex market trend.

### Dataset Source:

Publicly available: https://www.kaggle.com/datasets/gsdeepakkumar/gold-price-dataset

### Dataset Format:

File type: CSV
Number of rows: 2290
Number of columns: 6

## Installation
```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## How to Run (Windows)

```bash
# 1. Clone the repository
git clone https://github.com/Monishsasi/ML-Projects.git
cd ML-Projects

# 2. (Optional) Create a virtual environment
python -m venv venv

# 3. Activate the virtual environment (Windows)
venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the Jupyter Notebook
jupyter notebook "Gold Price Prediction.ipynb"


## Future Improvements
- Improve model accuracy with advanced algorithms.
- Integrate with web dashboards for real-time predictions.
- Use additional features for better insights.

## References
- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- Matplotlib Documentation: https://matplotlib.org/

