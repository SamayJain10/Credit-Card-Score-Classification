
# Credit Score Classification Project

## Overview
This project is centered around the classification and analysis of credit scores based on various financial parameters. Utilizing a comprehensive dataset, the notebook explores how different factors such as annual income, number of bank accounts, number of loans, and more, correlate with a person's credit score. Advanced visualization techniques are employed to provide insightful findings, and a machine learning model is developed for credit score prediction.

## Key Features
- **Data Exploration**: Investigates the relationships between various financial indicators and credit scores.
- **Visualization**: Uses Plotly for dynamic and interactive visual representations of the data.
- **Predictive Modeling**: Employs a Random Forest Classifier to predict credit scores based on financial indicators.

## Installation
To run this project, you need to install the following Python libraries:

```bash
pip install pandas numpy plotly scikit-learn
```

Note: This project uses Plotly for visualization, which provides interactive charts.

## Dataset
The dataset used in this project (`train.csv`) has been taken from Kaggle and includes various financial attributes of individuals, along with their credit scores. Key columns in the dataset include:
- `Annual_Income`
- `Occupation`
- `Num_Bank_Accounts`
- `Num_Credit_Card`
- `Num_of_Loan`
- `Credit_Score`
- ... and many more.

## Usage
1. **Data Analysis**: Explore how different financial variables relate to credit scores.
2. **Visualizations**: Interactive box plots and other charts to understand the distribution and relationships in the data.
3. **Predictive Model**: Use the Random Forest model to predict credit scores based on user input.

To use the predictive model, input the required financial data when prompted, and the model will output a credit score prediction.

## Insights and Findings
- The number of bank accounts, loans, and the delay in payments are inversely related to the credit score.
- Higher annual incomes generally correlate with better credit scores.
- Specific detailed insights for each financial variable are included in the notebook.

## Future Work
- Enhancing the model's accuracy with more sophisticated algorithms.
- Incorporating more features that could impact credit scores.
- Implementing a web interface for easier interaction with the predictive model.

