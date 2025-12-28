# Rental Duration Prediction – Model Development

## Objective
Predict the number of days a DVD will be rented using regression models while avoiding data leakage and maintaining strong generalization performance.

---

## Dataset
Source file: `rental_info.csv`

Target variable:
- `rental_length_days`

---

## Methodology
1. Converted rental and return timestamps to datetime
2. Engineered rental duration in days
3. Encoded special features using binary flags
4. Removed leakage-prone features
5. Split data into training and test sets
6. Evaluated multiple regression models

---

## Models Evaluated
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor

---

## Evaluation Metric
- Mean Squared Error (MSE)

---

## Final Model
- **Model:** Random Forest Regressor  
- **Test MSE:** ~2.03

---

## Output
- Trained regression model
- Comparative model performance
- Business-ready insights for inventory planning
