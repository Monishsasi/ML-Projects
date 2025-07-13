
# Coffee Shop Revenue Prediction

## Project Overview
Developed a machine learning model using **Linear Regression** to predict daily revenue for a coffee shop. This prediction is based on features such as customer count, order value, and marketing spend.

## Features
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Input Scaling
- Model Training and Evaluation

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Results
- Achieved an R² score of ~0.89 indicating strong predictive performance.
- Low error rates on both training and testing datasets.

## Usage
1. Load and preprocess the dataset.
2. Train the Linear Regression model.
3. Evaluate model performance.
4. Predict future revenue based on new data inputs.


## Dataset Description

The Coffee Shop Revenue Prediction Dataset contains 2000 records capturing daily operational metrics of a coffee shop, aimed at predicting the daily revenue based on various business factors.

### Feature Description:

Number_of_Customers_Per_Day - Total number of customers visiting per day.
Average_Order_Value - Average value of a single customer order (in currency units).
Operating_Hours_Per_Day - Number of hours the coffee shop operates per day.
Number_of_Employees - Total number of employees working that day.
Marketing_Spend_Per_Day - Amount spent on marketing activities per day.
Location_Foot_Traffic - The number of people passing by the shop location each day.
Daily_Revenue - Total revenue generated each day — this is the target variable for prediction.

### Dataset Details:

Number of records (rows): 2000
Number of features (columns): 7
File format: CSV

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
jupyter notebook "Coffee Shop Revenue.ipynb"

## Future Improvements
- Improve model accuracy with advanced algorithms.
- Integrate with web dashboards for real-time predictions.
- Use additional features for better insights.

## References
- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- Matplotlib Documentation: https://matplotlib.org/

