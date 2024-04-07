## Loan Approval Prediction
This project is about predicting loan approval using machine learning models. The dataset used in this project is a collection of loan applicants’ data.

## Project Description
The goal of this project is to predict whether a loan will be approved or not based on various features such as Gender, Married status, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area.

## Data
The data used in this project is a collection of loan applicants’ data. The data includes the following columns:

- Loan_ID: Unique Loan ID
- Gender: Male/ Female
- Married: Applicant married (Y/N)
- Dependents: Number of dependents
- Education: Applicant Education (Graduate/ Under Graduate)
- Self_Employed: Self-employed (Y/N)
- ApplicantIncome: Applicant income
- CoapplicantIncome: Coapplicant income
- LoanAmount: Loan amount in thousands
- Loan_Amount_Term: Term of the loan in months
- Credit_History: Credit history meets guidelines
- Property_Area: Urban/ Semi Urban/ Rural
- Loan_Status: Loan approved (Y/N)

## Methodology
The project involves several steps:

- **Data Loading and Preprocessing**: The data is loaded using pandas and preprocessed. The preprocessing steps include dropping unnecessary columns, handling missing values, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: EDA is performed to understand the distribution of the data and the relationship between different features. This includes creating bar plots and heatmaps.
- **Model Training**: Four different machine learning models are trained on the data: RandomForestClassifier, KNeighborsClassifier, SVC, and LogisticRegression.
- **Model Evaluation**: The models are evaluated based on their accuracy score. The model with the highest accuracy score is selected as the final model.

## Results
The RandomForestClassifier model achieved the highest accuracy of 98.04%.

## Usage
To run the project, you need to have Python installed on your machine. You also need to install the necessary libraries, which include numpy, pandas, matplotlib, seaborn, sklearn.

You can run the project by executing the Python script in a Python environment.

## Contributing
Contributions are welcome. Please feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
This project is licensed under the MIT License. See the LICENSE file for details.
