# Rental Days Prediction

## Description
This project predicts the number of rental days for properties using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation. The notebook demonstrates the use of regression algorithms, such as Random Forest and Linear Regression, to estimate rental durations based on features like rental_rate and some special features. Results are visualized to highlight key predictors. The goal is to provide accurate rental day forecasts to assist property managers in planning and decision-making. The dataset is included in the repo

## Features
- Exploratory Data Analysis (EDA) of rental datasets
- Data cleaning
- Data preprocessing and visualization
- Model training and evaluation 

## Requirements
All necessary dependencies are listed in the `requirements.txt` file.  
To install them, run:
```bash
pip install -r requirements.txt
```

## 📊 Model Performance
After training several models, the best performing result came from using a Random Forest Regressor:
- R² Score: 0.7148
- RMSE: ~1.4229

## Usage
1. Prepare your own rental dataset or use the provided sample data.
2. Adjust the data path in `notebook.ipynb` if using a different dataset.
3. Run each section of the notebook to perform EDA, data cleaning, preprocessing, and model training.
4. Review the model evaluation metrics to assess prediction performance.
5. Modify features or models as needed to improve results or adapt to your data.

## Results
- Model performance is evaluated using metrics like RMSE and R2.
- Feature importance plots highlight key predictors.
- Visualizations compare predicted vs. actual rental days.

## License
This project is licensed under the MIT License.