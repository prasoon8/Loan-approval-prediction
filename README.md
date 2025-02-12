# Loan Approval Prediction

## Overview
This project aims to predict whether a loan application will be approved based on various applicant attributes. Using machine learning techniques, the model analyzes key factors such as applicant income, credit history, loan amount, and more to make informed predictions.

## Dataset
The dataset used for this project (`loan.csv`) contains information about past loan applications, including features like:
- Applicant Income
- Loan Amount
- Credit History
- Property Area
- Marital Status
- Employment Status
- Education Level
- Number of Dependents

## Methodology
The project follows a structured machine learning pipeline:

1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling and selection
   
2. **Exploratory Data Analysis (EDA):**
   - Understanding the data distribution
   - Identifying correlations between features
   - Visualizing key insights

3. **Model Selection & Training:**
   - Tried different machine learning models including:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - XGBoost
   - Used GridSearchCV for hyperparameter tuning

4. **Model Evaluation:**
   - Performance measured using accuracy, precision, recall, and F1-score
   - Used k-fold cross-validation for better generalization

## Results
The best-performing model achieved high accuracy in predicting loan approvals, demonstrating its potential for real-world applications in banking and finance.

## Installation & Usage
To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/prasoon8/Loan-approval-prediction.git
   cd Loan-approval-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook (`Loan.ipynb`) to explore and train the model.

## Future Improvements
- Enhance feature engineering techniques
- Implement deep learning models for better accuracy
- Deploy the model as a web application for user interaction

## Contributors
- **Prasoon8** 

## License
This project is open-source and available under the [MIT License](LICENSE).

