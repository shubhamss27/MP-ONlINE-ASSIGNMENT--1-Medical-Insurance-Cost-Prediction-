# Medical Insurance Cost Prediction
# Medical Insurance Cost Prediction using Multiple Linear Regression

## Student Details

**Name:** Shubham Kadwe  
**Registration Number:** 23MIP10137

---

## Objective
The objective of this project is to predict medical insurance charges using Multiple Linear Regression based on customer information such as age, sex, BMI, number of children, smoking status, and region.

## Dataset Link
https://www.kaggle.com/datasets/mirichoi0218/insurance

## Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn

## Methodology
1. Load the dataset using Pandas.
2. Display the first five records.
3. Identify numerical and categorical features.
4. Check for missing values.
5. Encode categorical variables (sex, smoker, region).
6. Split the dataset into 80% training and 20% testing.
7. Train a Multiple Linear Regression model.
8. Predict insurance charges.
9. Evaluate the model using MAE, MSE, and R² Score.
10. Plot Actual vs Predicted values.

## Results
- **Mean Absolute Error (MAE):** 4186.51
- **Mean Squared Error (MSE):** 33635210.43
- **R² Score:** 0.7833

The model achieved good prediction performance and explained approximately **78.33%** of the variance in insurance charges.

## Conclusion
This project successfully developed a Multiple Linear Regression model to predict medical insurance charges using customer information. The model achieved an R² score of approximately 0.78, indicating good predictive performance. Smoking status, BMI, and age were found to have the greatest influence on insurance charges. Although the model performs well overall, prediction errors still exist for some extreme values because Linear Regression assumes a linear relationship between variables.
Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance
