
# Diabetes Prediction

## Project Overview
Implemented a **Support Vector Classifier (SVC)** to predict the likelihood of diabetes based on patient health metrics.

## Features
- Data Preprocessing (Cleaning and Standard Scaling)
- Model Training and Testing
- Performance Evaluation

## Tools & Technologies
- Python
- Scikit-learn
- Pandas
- StandardScaler

## Results
- Achieved a test set accuracy of **77.2%**.
- Balanced feature contributions via standard scaling.

## Usage
1. Load health metrics dataset.
2. Preprocess data.
3. Train the SVC model.
4. Make predictions and evaluate results.


## Dataset Description

The Diabetes Prediction Dataset consists of 768 records of medical data related to women of Pima Indian heritage. The goal is to predict whether a patient has diabetes based on diagnostic measurements.

### Feature Description:

Pregnancies - Number of times the patient has been pregnant.
Glucose	Plasma - glucose concentration (after 2 hours in an oral glucose tolerance test).
BloodPressure - Diastolic blood pressure (mm Hg).
SkinThickness - Triceps skin fold thickness (mm).
Insulin - 2-Hour serum insulin (mu U/ml).
BMI - Body Mass Index (weight in kg/(height in m)^2).
DiabetesPedigreeFunction - A function that scores the likelihood of diabetes based on family history.
Age - Age of the patient (years).
Outcome - Diabetes test result: 1 for positive, 0 for negative.

### Dataset Source:

Publicly available: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

### Dataset Format:

File type: CSV
Number of rows: 768
Number of columns: 9

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
jupyter notebook "Diabetes Prediction.ipynb"


## Future Improvements
- Improve model accuracy with advanced algorithms.
- Integrate with web dashboards for real-time predictions.
- Use additional features for better insights.

## References
- Scikit-learn Documentation: https://scikit-learn.org/
- Pandas Documentation: https://pandas.pydata.org/
- Matplotlib Documentation: https://matplotlib.org/

