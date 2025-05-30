# Titanic Survival Prediction

This project analyzes the famous Titanic dataset to predict passenger survival using machine learning techniques. The analysis includes comprehensive data exploration, feature engineering, and model development.

## Project Overview

The goal of this project is to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, ticket class, fare, and more. The project follows a structured approach to data analysis and machine learning model development.

## Repository Structure

```
titanic-survival/
├── data/               # Dataset files
│   ├── train.csv      # Training data
│   └── test.csv       # Test data
├── notebooks/         # Jupyter notebooks
│   └── Titanic_01.ipynb
├── requirements.txt   # Project dependencies
└── README.md         # Project documentation
```

## Dataset

The dataset contains information about passengers aboard the Titanic, including:
- Passenger demographics (age, gender, class)
- Ticket information (fare, cabin, embarkation port)
- Family relationships (sibsp, parch)
- Survival status (target variable)

## Analysis Steps

1. **Data Loading and Initial Exploration**
   - Loading the dataset
   - Basic statistical analysis
   - Data type inspection
   - Missing value analysis

2. **Data Cleaning and Preprocessing**
   - Handling missing values
   - Converting data types

3. **Feature Engineering**
   - Creating new features from existing ones
   - Extracting titles from names
   - Binning continuous variables
   - Encoding categorical variables

4. **Model Development**
   - Data splitting (train/validation)
   - Model training (Logistic Regression)
   - Hyperparameter tuning
   - Model evaluation

## Results

The final model achieved the following performance metrics:
- Accuracy: 0.838
- ROC-AUC: 0.870

Key findings:
- Gender was the most important predictor of survival
- Passenger class and fare were significant factors
- Family size had a moderate impact on survival chances

## Model Performance

The model shows good performance with:
- High precision and recall for both classes
- Balanced performance across different metrics
- Strong ROC-AUC score indicating good discrimination ability

## Future Improvements

1. **Model Enhancements**
   - Implement ensemble methods (Random Forest, XGBoost)
   - Apply K-Fold cross-validation
   - Use SHAP for model interpretation

2. **Feature Engineering**
   - Create more sophisticated feature combinations
   - Explore interaction terms
   - Consider feature selection techniques

3. **Deployment**
   - Develop a web application using Streamlit or Flask
   - Create an API for predictions
   - Add real-time prediction capabilities

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Installation

1. Clone the repository
2. Install required packages:
```bash
pip install -r requirements.txt
```
3. Place the dataset files (`train.csv` and `test.csv`) in the `data/` directory
4. Run the Jupyter notebook `notebooks/Titanic_01.ipynb`

## Author

Razuldev

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
