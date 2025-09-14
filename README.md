# oasis_inbt_Car_Prize_Pridiction-

# Car Price Prediction with Machine Learning



Click on the following link to checkout the colab file.
- [Colab](https://colab.research.google.com/github/vannalevaibhav-rcb/oasis_inbt_Car_Prize_Pridiction-/blob/main/Car_Price_Prediction_with_Machine_Learning.ipynb)


**Key Objectives:**

- Explore the factors affecting car prices.
- Create a machine learning model to predict car prices.
- Gain valuable experience in the field of machine learning and automotive pricing.

---

## Project Summary

**Objective:** Develop a machine learning model to predict car prices based on various influencing factors.

**Why Car Price Prediction?** Car prices are influenced by numerous variables, including brand reputation, features, horsepower, and fuel efficiency. Machine learning models can provide accurate price predictions.

**Key Tasks:**

1. **Data Collection:** Gather data on various car attributes and their corresponding prices.
2. **Data Preprocessing:** Clean, transform, and prepare the data for modeling.
3. **Feature Engineering:** Identify the most important features for price prediction.
4. **Model Building:** Create a machine learning model capable of predicting car prices.
5. **Model Evaluation:** Assess the model's accuracy and performance using appropriate metrics.
6. **Deployment:** Make the trained model available for car price predictions.

**Benefits:** By completing this project, we'll gain valuable insights into machine learning, data analysis, and the automotive industry. We'll also have a functional car price prediction model that can be useful for future car pricing decisions.

---

## Results

I have selected R2 score as the primary evaluation metric for the Car Price Prediction model. And after removing the overfitted models which have MSE, R2 score, Adjusted R2 score for train as 100% and also have negative accuracy value, we get the final list:

| Sl. No. | Regression Model      |   R2 Train (%) |   R2 Test (%) |
|:--------|:--------------------------|---------------:|--------------:|
|    1    | Linear Regression         |       64.21  |      49.24 |
|    2    | Linear Regression tuned       |       64.21  |      49.24 |
|    3    | Lasso Regression tuned       |       63.62 |      49.57 |
|    4    | Ridge Regression         |       64.19 |      49.36 |
|    5    | Ridge Regression tuned        |       63.92 |      50.22 |
|    6    | Decision Tree tuned         |       76.00 |      70.37 |
|    7    | Random Forest         |       98.61 |      93.05 |
|    8    | Random Forest tuned        |       77.10 |      73.71 |
|    9    | Gradient Boosting Regressor         |       98.78 |      90.47 |
|    10    | Gradient Boosting Regressor tuned        |       96.11 |      88.24 |

## Conclusion

This project explores the automotive industry's intricate dynamics, aiming to predict car prices with machine learning. By analyzing various factors such as fuel type, seller type, and transmission, we uncover valuable insights and select a robust model for accurate price prediction.



## Author

- [Vaibhav Vannale](www.linkedin.com/in/vaibhav-vannale-2a051b28a)

---

## Reference
 - [Oasis Infobyte](https://oasisinfobyte.com/)
