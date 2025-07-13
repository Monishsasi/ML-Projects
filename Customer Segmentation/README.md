
# Customer Segmentation

## Project Overview
Implemented **K-Means Clustering** to segment customers based on behavioral and demographic data.

## Features
- Unsupervised Learning Approach
- Optimal Cluster Identification using Elbow Method
- Data Visualization

## Tools & Technologies
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Results
- Achieved a well-defined segmentation with **WCSS of 5**.

## Usage
1. Load customer data.
2. Apply K-Means Clustering.
3. Determine the optimal number of clusters.
4. Visualize segmented data.


## Dataset Description

The Mall Customer Segmentation Dataset consists of 200 records with the following features:

### Feature Description:

CustomerID - Unique ID assigned to each customer.
Gender - Gender of the customer (Male/Female).
Age - Age of the customer (in years).
Annual Income (k$) - Annual income of the customer (in thousands of USD).
Spending Score (1-100) - Score assigned by the mall based on customer spending behavior and patterns.

### Dataset Source:

The dataset is publicly available and can be downloaded from:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial

### Dataset Format:

File type: CSV
Number of rows: 200
Number of columns: 5

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
jupyter notebook "Customer Segmentation.ipynb"


## Future Improvements
- Improve model accuracy with advanced algorithms.
- Integrate with web dashboards for real-time predictions.
- Use additional features for better insights.

## References
- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- Matplotlib Documentation: https://matplotlib.org/

