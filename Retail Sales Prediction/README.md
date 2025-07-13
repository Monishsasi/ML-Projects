
# Retail Sales Forecasting Model

## Project Overview
Built a **Decision Tree Regressor** to forecast item sales across multiple retail outlets. Optimized model performance using **GridSearchCV** for hyperparameter tuning.

## Features
- Data Cleaning
- Data Visualization
- Feature Selection
- Hyperparameter Tuning

## Tools & Technologies
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Results
- Achieved an R² score of ~0.6.
- Enhanced model accuracy through systematic parameter tuning.

## Usage
1. Prepare the dataset.
2. Train the Decision Tree Regressor.
3. Fine-tune hyperparameters using GridSearchCV.
4. Predict future sales.


## Dataset Description
The Retail Sales Forecasting Dataset consists of 8523 records, containing information about various products sold across multiple retail outlets, along with sales data. The goal is to predict the Item Outlet Sales, which represents the sales of products in different stores.

### Feature Description

Item_Identifier - Unique identifier for each product.
Item_Weight - Weight of the product.
Item_Fat_Content - Fat content of the product (e.g., Low Fat, Regular).
Item_Visibility - The percentage of total display area allocated to the product in a store.
Item_Type - Category/type of the product.
Item_MRP - Maximum Retail Price of the product.
Outlet_Identifier - Unique identifier for each store.
Outlet_Establishment_Year - Year the store was established.
Outlet_Size - Size of the store (e.g., Small, Medium, High).
Outlet_Location_Type - Location tier of the store (e.g., Tier 1, Tier 2, Tier 3).
Outlet_Type - Type of the store (e.g., Supermarket Type1, Grocery Store).
Item_Outlet_Sales - Target variable — sales of the product in the store.

### Dataset Source:

Publicly available: https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data

### Dataset Format:

File type: CSV
Number of records: 8523
Number of features (columns): 12

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
jupyter notebook "Big Mart Sales Prediction.ipynb"


## Future Improvements
- Improve model accuracy with advanced algorithms.
- Integrate with web dashboards for real-time predictions.
- Use additional features for better insights.

## References
- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- Matplotlib Documentation: https://matplotlib.org/

