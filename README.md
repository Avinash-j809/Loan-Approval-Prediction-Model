#Loan Approval Prediction using Machine Learning

#Overview
This project builds a classification model to predict loan approval based on applicant financial and demographic data. The goal is to support structured credit decision making using machine learning.

Business Context
Banks must assess loan applications while managing risk. A predictive model helps standardize approvals and reduce manual bias.

Dataset
The dataset contains applicant details such as income, loan amount, credit history, education, employment status, and property area.
Target variable: Loan_Status.

Approach

• Data cleaning and missing value treatment
• Exploratory data analysis
• Categorical feature encoding
• Train test split
• Model training and evaluation

Models Used

• Logistic Regression
• Decision Tree
• Random Forest

Evaluation

Models were compared using accuracy and confusion matrix metrics.
Random Forest performed best. Credit history emerged as the strongest approval driver.

Tech Stack

• Python
• Pandas
• NumPy
• Scikit learn
• Matplotlib
• Seaborn

How to Run

Clone the repository

Install dependencies using pip install -r requirements.txt

Open the notebook in Jupyter

Future Improvements

• Hyperparameter tuning
• Cross validation
• Model deployment
• Integration with a credit risk scoring framework
