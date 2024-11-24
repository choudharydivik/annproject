## End to End Deep Learning Project Using ANN
### Bank Customer Churn Prediction

This project predicts whether a customer will leave the bank (churn) or stay, using an Artificial Neural Network (ANN). Below are the key details and steps involved in the project.

---

#### Features

The dataset includes the following features:

- **RowNumber**: Unique index for each record
- **CustomerId**: Unique identifier for each customer
- **Surname**: Customer's last name
- **CreditScore**: Customer's credit score
- **Geography**: Country of the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Tenure**: Duration of the customer’s relationship with the bank (in years)
- **Balance**: Customer’s account balance
- **NumOfProducts**: Number of products the customer is using
- **HasCreditCard**: Indicates if the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Indicates if the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Customer’s estimated salary
- **Exited**: Target variable (1 = Exited, 0 = Stayed)

---

## Steps Involved

### 1. Data Preparation
- Data preprocessing and cleaning using **sklearn**.
- Feature transformation to scale numerical data and encode categorical features.

### 2. Building the ANN
- An Artificial Neural Network is designed and built step by step:
  - **Input Layer**
  - **Hidden Layers**
  - **Output Layer**
- Activation functions, optimizers, and loss functions are carefully chosen for binary classification.

### 3. Training the ANN
- Training is performed using various optimization techniques.
- If the training accuracy does not meet expectations, hyperparameter tuning is conducted to improve performance.

### 4. Making Predictions
- The trained ANN model is used to predict whether a customer will exit the bank.
- Evaluation metrics are applied to validate model performance.

### 5. Web Application Integration
- The ANN model is integrated with a **Streamlit** web application.
- The app allows users to input customer details and predict churn probability in real-time.

### 6. Deployment
- The Streamlit web application is deployed on **Streamlit Cloud** for public access.
- The deployment ensures scalability and easy access to the churn prediction tool.

---

