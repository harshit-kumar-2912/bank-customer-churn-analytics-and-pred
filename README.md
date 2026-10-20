# Bank Customer Churn Analytics and Prediction

**Harshit Kumar** · [GitHub](https://github.com/harshit-kumar-2912)

My banking customer churn analytics portfolio project brings together SQL, Python, statistics, machine learning, and Tableau. It explores customer churn through data preparation, relational analysis, statistical testing, and predictive modeling.

## Business objective

The aim is to understand which customer and account characteristics are associated with churn and explore how predictive models can support customer retention decisions.

The project covers:

- Preparing demographic, account, and geographic data for analysis.
- Organizing the data into a relational SQL Server schema.
- Exploring churn patterns using SQL and statistical hypothesis tests.
- Engineering features and comparing classification models.
- Presenting the analysis through a Tableau workbook and supporting documentation.

## Project workflow

1. **Data preparation:** Python scripts inspect and clean the raw data, with processed tables stored as CSV files.
2. **Relational modeling:** A SQL Server schema connects demographic, account, and location tables. The documentation includes an entity relationship diagram.
3. **Exploratory analysis:** SQL queries examine churn across customer segments.
4. **Statistical analysis:** A notebook explores relationships using hypothesis testing, including t-tests, chi-square tests, and ANOVA.
5. **Predictive modeling:** Preprocessing creates features such as balance-to-salary ratio and tenure-to-age ratio, scales numeric features, and encodes categorical variables. Experiment notebooks cover logistic regression, random forest, SVM, and XGBoost.
6. **Evaluation and visualization:** The evaluation helper reports churn recall, precision, F1, and ROC AUC. A Tableau workbook supports visual exploration of the analysis.

## Repository guide

| Folder | Contents |
| --- | --- |
| [data](data/) | Raw Excel data and processed account, demographic, and location tables |
| [scripts](scripts/) | Data cleaning, SQL ingestion, and utility scripts |
| [eda_queries](eda_queries/) | SQL queries for exploratory analysis |
| [statistical_testing](statistical_testing/) | Statistical analysis notebook |
| [predictive_modelling](predictive_modelling/) | Model experiments, evaluation helper, and preprocessing artifacts |
| [data_visualization](data_visualization/) | Tableau workbook |
| [documentation](documentation/) | Problem definition, data documentation, ERD, and visual references |

## Tools and technologies

Python, pandas, NumPy, scikit-learn, XGBoost, joblib, pyodbc, SQL Server, Jupyter Notebook, and Tableau.

## Exploring the project

1. Start with the problem definition and data documentation in [documentation/docs](documentation/docs/).
2. Review the raw and processed datasets in [data](data/), then inspect the cleaning scripts and SQL schema in [scripts](scripts/).
3. Explore the SQL queries, statistical notebook, and model experiment notebooks.
4. Open [Churn Prediction.twb](<data_visualization/Churn Prediction.twb>) in Tableau and update its data connections for your environment.

To execute the Python and SQL workflows, install the packages used by the scripts and notebooks, configure SQL Server and an appropriate ODBC driver, and update the local server names and file paths. The ingestion script contains separate table-loading sections; check that each section reads its matching processed CSV before running it.

The repository contains analysis and model experiments. It does not include a deployed prediction service or a consolidated automated training command.

## About me

I'm Harshit Kumar. This repository is part of my data analytics and machine learning portfolio, with a focus on connecting customer data analysis to practical business questions.

[View my GitHub profile](https://github.com/harshit-kumar-2912)