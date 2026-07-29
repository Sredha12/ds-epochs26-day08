# Customer Churn Prediction – Model Optimization

**Name:** SREDHA MANOJ
**MUID:** sredhamanoj-1@mulearn

---

# Project Summary

This project focuses on predicting customer churn using machine learning classification models. A baseline model was first developed and evaluated. The model was then optimized using **GridSearchCV** to improve its predictive performance. Finally, the optimized model was compared with the baseline model, and feature importance analysis was performed to identify the major factors influencing customer churn.

---

# Dataset

* **Dataset:** Customer Churn Dataset
* **Source:** Kaggle
* **Target Variable:** Churn

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# Machine Learning Workflow

1. Data Loading
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Encoding and Scaling
5. Train-Test Split
6. Baseline Model Training
7. Model Evaluation
8. Hyperparameter Tuning using GridSearchCV
9. Optimized Model Evaluation
10. Feature Importance Analysis

---

# Baseline Models

The following classification models were implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

Each model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

# Optimization Approach

The Random Forest model was optimized using **GridSearchCV** with cross-validation. Different combinations of hyperparameters, including the number of estimators, maximum tree depth, minimum samples split, and minimum samples per leaf, were tested to identify the best-performing model.

The optimized model obtained the best hyperparameter combination and was retrained using these parameters before evaluating its performance on the test dataset.

---

# Model Improvements

After hyperparameter tuning:

* The optimized Random Forest model achieved improved predictive performance compared to the baseline model.
* The optimized model provided better generalization on unseen data.
* Performance metrics were compared to demonstrate the effectiveness of optimization.

---

# Important Observations

Feature importance analysis indicated that several customer-related factors have a significant influence on churn prediction. Features such as **Support Calls**, **Payment Delay**, **Tenure**, **Total Spend**, and **Usage Frequency** contributed strongly to the model's decisions.

These insights help identify customers who are at a higher risk of leaving the service.

---

# Recommendations

* Improve customer support quality to reduce repeated support calls.
* Reduce payment delays by providing timely reminders and flexible payment options.
* Increase customer engagement during the initial subscription period.
* Encourage customers to choose long-term contracts through attractive offers.
* Identify high-risk customers early and provide personalized retention strategies.

---

# Conclusion

This project demonstrates how machine learning can effectively predict customer churn. Hyperparameter tuning using GridSearchCV improved the performance of the Random Forest model compared to the baseline model. Feature importance analysis provided valuable insights into the major factors contributing to customer churn, enabling businesses to make informed decisions for improving customer retention.

---

**Repository Contents**

* `model_optimization.ipynb`
* `README.md`
