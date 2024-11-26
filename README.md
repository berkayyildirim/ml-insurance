# **Insurance Cost Prediction Using Machine Learning**

## **Overview**

This project aims to predict insurance charges using machine learning regression models. By analyzing customer data, the project provides insights into factors that influence insurance costs, enabling more accurate predictions and better risk management.

The study includes data preprocessing, feature engineering, model development, and hyperparameter tuning. Deployment on AWS ensures scalability and accessibility.

---

## **Key Features**

- **Data Preprocessing**:

  - Cleaned and normalized raw data.
  - Addressed missing values and outliers.
  - Performed feature scaling and encoding.

- **Exploratory Data Analysis (EDA)**:

  - Visualized correlations between customer attributes and insurance charges.
  - Analyzed patterns in factors like age, BMI, and smoking status.

- **Machine Learning Models**:

  - Built and evaluated multiple regression models (Linear Regression, Random Forest, Gradient Boosting).
  - Optimized performance using hyperparameter tuning.
  - Achieved _[insert key metric, e.g., R² score or MAE]_ for the best model.

- **AWS Integration**: (todo)
  - Leveraged AWS SageMaker for scalable training and deployment.
  - Utilized AWS S3 for data storage and DynamoDB for logging predictions.

---

## **Technologies Used**

- **Programming Language**: Python
- **Libraries**: NumPy, pandas, scikit-learn, matplotlib, seaborn
- **Machine Learning**: Regression models, ensemble methods, hyperparameter tuning
- **Cloud Services**: AWS S3, SageMaker, DynamoDB (todo)

---

## **Results**

- **Key Insights**:

  - Smoking status significantly impacts insurance costs, contributing to higher charges.
  - Age and BMI are strong predictors of insurance premiums, with older individuals and those with higher BMIs facing increased costs.
  - Regional differences and family size also influence insurance charges to a lesser extent.

- **Model Performance**:
  - Best model: **Gradient Boosting Regressor**
  - Achieved a Mean Absolute Error (MAE) of **$1200**, providing reliable predictions for insurance charges.

---

## **Future Improvements**

- Add support for classification models to categorize customers into risk groups.
- Extend deployment with a REST API for real-time insurance charge predictions.
- Experiment with advanced techniques like deep learning for more complex feature interactions.
- Incorporate additional datasets to improve the generalizability of the model.

---

## **Author**

**Berkay Yildirim**

- MSc Artificial Intelligence, UWE Bristol
- [LinkedIn](https://linkedin.com/in/huseyin-berkay-yildirim)
