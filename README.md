# Customer Churn Prediction using Random Forest

A concise machine learning workflow for predicting telecom customer churn using
the **Random Forest Classifier**. This project uses the IBM Telco Customer Churn
dataset and demonstrates preprocessing, model training, evaluation, and tree 
visualization.

# Dataset
The dataset is loaded directly from IBM’s public repository:

https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

# Workflow Overview
1. Import essential Python libraries 
2. Load and inspect the dataset
3. Encode categorical features using LabelEncoder
4. Split data into training and testing sets (80/20)
5. Train a Random Forest model with 100 trees and max depth of 4
6. Evaluate performance using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
7. Plot feature importance to understand key churn indicators
8. Visualize:
   - A single decision tree
   - Multiple trees inside the Random Forest ensemble

# Model Performance
- The model predicts customer churn based on service usage and customer profile.
- Accuracy, precision, recall, and F1-score are reported for performance tracking.

# Visual Outputs
- Confusion Matrix Heatmap
- Feature Importance Bar Plot
- Decision Tree Visualization
- 4-tree ensemble visualization demonstrating randomness

# Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

# How to Run
1. Install required libraries:
   pip install pandas scikit-learn matplotlib seaborn
2. Run the notebook or Python script
3. View generated metrics and visualizations

# Purpose
This project demonstrates how ensemble decision-tree methods can effectively
predict churn and provide explainability through visual model interpretation.
