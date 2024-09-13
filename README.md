# Customer Churn Prediction for a Travel & Tourism Company

This project focuses on predicting customer churn for a travel and tourism company using machine learning techniques. The aim is to identify customers who are likely to stop using the service, allowing the company to take proactive measures to retain them.

## Project Workflow:

### 1. Exploratory Data Analysis (EDA):
A comprehensive EDA was performed to understand the structure of the dataset, identify missing values, and explore relationships between features and churn. This helped in identifying key drivers behind customer behavior and allowed us to visualize patterns that influence customer churn.

### 2. Feature Engineering:
After analyzing the dataset, feature engineering techniques were applied to enhance predictive power. Features were selected and transformed based on domain knowledge and data-driven insights, which ensured the model could capture the important factors contributing to churn.

### 3. Model Architecture:
The model was built using TensorFlow and has the following structure:
- **Input layer:** 7 dimensions representing customer-related features.
- **Hidden layer:** 3 neurons with ReLU activation.
- **Output layer:** 1 neuron with a sigmoid activation function for binary classification.

The model was compiled with the following settings:
- **Loss function:** `binary_crossentropy`
- **Optimizer:** `Adam`
- **Evaluation metric:** Accuracy

### 4. Results:
The model achieved an accuracy of 85% on the test set, demonstrating its effectiveness in predicting churn. This provides a valuable tool for the company to reduce churn and improve customer retention.

### 5. How to Use:
- Clone the repository.
- Install dependencies from `requirements.txt`.
- Run the model on your data using the provided Jupyter notebook.

This model serves as a starting point for improving customer retention strategies in the travel and tourism sector, providing actionable insights into customer behavior.
