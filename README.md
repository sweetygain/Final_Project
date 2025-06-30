# Final_Project
This project analyzes HR data to predict employee attrition and understand the factors contributing to it. It combines machine learning, SHAP explainability, and Power BI for end-to-end HR analytics.

Tools & Technologies:
- Python (Pandas, Seaborn, Scikit-learn, SHAP)
- Power BI
- Jupyter Notebook
-------

Project Structure:
├── data
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── notebooks
│   └── attrition_analysis.ipynb
├── powerbi
│   └── HR_Attrition_Dashboard.pbix
├── shap
│   └── shap_summary.png
├── report
│   └── HR_Attrition_Report.pdf
└── README.md

--------

Key Features:
- Exploratory Data Analysis (EDA) by department, gender, age, and income.
- Logistic regression & Decision Tree classifier to predict attrition.
- SHAP value analysis to explain model predictions.
- Interactive Power BI dashboard with age/attrition cards and slicers.

---------

How to Run:
- Clone this repo
- Open notebooks/attrition_analysis.ipynb to view the EDA and model
- Open powerbi/HR_Attrition_Dashboard.pbix in Power BI Desktop
- View SHAP plots in shap/

----------

Results:
- Best model: Decision Tree (Recall = 23% for attrition class)
- Key attrition factors: OverTime, Monthly Income, Job Role, Age



