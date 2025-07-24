# Customer Churn Prediction
## This project uses a machine learning pipeline to predict customer churn based on historical customer data. The pipeline includes preprocessing, encoding, scaling, model training, and evaluation.

### Project Steps
1. Drop missing values.
2.  Drop the CustomerID column.
3.  Encode categorical variables:
    - Label Encoding for binary columns like Gender.
    - One-Hot Encoding for non-binary columns like Subscription Type and Contract Length.
4. Scale numerical features.
5. Use ColumnTransformer and Pipeline to streamline preprocessing and model training.
6. Train a Random Forest classifier.
7. Evaluate using classification metrics.

### Dataset Features
- Numerical: Age, Tenure, Usage Frequency, Support Calls, Payment Delay, Total Spend, Last Interaction
- Binary Categorical: Gender
- Multi-class Categorical: Subscription Type, Contract Length

### Requirements
- pandas
- numpy
- scikit-learn

### How to Run
Install dependencies:
- nginx
- Copy
- Edit
- pip install -r requirements.txt
- Place the dataset as data.csv.

Run the script or Jupyter Notebook to train and evaluate the model.

Output
The model outputs a classification report showing precision, recall, and F1-score.
