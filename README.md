# Sales-Prediction
## Overview
This project aims to predict car purchase amounts based on customer demographics and financial details using a machine learning model. The dataset consists of customer attributes such as age, income, and credit card debt.

## Objectives
- Perform data preprocessing and feature encoding
- Apply feature scaling to standardize data
- Train a machine learning model to predict car purchase amounts
- Evaluate model performance using regression metrics

## Dataset
The dataset contains the following columns:
- `customer name` (dropped during preprocessing)
- `customer e-mail` (dropped during preprocessing)
- `country` (one-hot encoded)
- `age`
- `annual salary`
- `credit card debt`
- `net worth`
- `car purchase amount` (target variable)

## Requirements
Ensure you have the following installed:
- Python (>=3.8)
- Jupyter Notebook or any Python IDE
- Required libraries:
  ```bash
  pip install pandas numpy scikit-learn
  ```

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-purchase-prediction.git
   cd car-purchase-prediction
   ```
2. Place the `car_purchasing.csv` dataset in the project directory.
3. Open and run the script in a Jupyter Notebook or execute `main.py`:
   ```bash
   python main.py
   ```
4. The script will preprocess the data, train a RandomForestRegressor model, and output evaluation metrics.


```

## Machine Learning Model Used
- **Random Forest Regressor** (with 100 estimators and random state 42)

## Evaluation Metrics
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

## Contributing
Feel free to submit pull requests or report issues. Contributions are welcome!

## License
This project is licensed under the MIT License.
