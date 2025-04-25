# Red Wine Quality - Regression and Classification Analysis: 
## Wine Quality Prediction using Machine Learning

This project focuses on predicting the quality of wine based on various chemical attributes using machine learning models. The dataset includes various features such as acidity, alcohol content, pH, and sulfur dioxide levels to predict the wine quality score (ranging from 1 to 10).

## Key Steps

1. **Data Preprocessing**  
   - Data cleaning and feature engineering techniques were applied, including handling missing values and transforming variables using methods like Box-Cox and logarithmic transformations.
   
2. **Feature Selection**  
   - Relevant features were selected using Recursive Feature Elimination (RFE) to enhance model performance and reduce overfitting.
   
3. **Modeling**  
   - Several machine learning models were trained, including Linear Regression, Random Forest Regressor, and Random Forest Classifier.
   - Hyperparameter tuning was done using K-Fold cross-validation to improve the model's generalization.
   
4. **Evaluation**  
   - Models were evaluated using metrics such as Root Mean Squared Error (RMSE), R-squared (R²), and classification accuracy, depending on whether regression or classification was performed.

5. **Results**  
   - The best-performing model was selected based on evaluation metrics, and it provides predictions on the wine quality based on input chemical features.

## Dependencies

- `pandas`
- `seaborn`
- `matplotlib`
- `numpy`
- `scikit-learn`

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/wine-quality-prediction.git
