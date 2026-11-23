# Data-Driven Analysis of Success and Failure Factors in Indian Startups

A data science project based on the Indian startup ecosystem. The project analyzes startup data to understand patterns related to **funding, funding rounds, location, and startup success or failure**.

## -> Project Objective

The main objective of this project is to analyze Indian startup data and compare successful and failed startups.

The project also studies the relationship between funding-related variables and uses statistical and data science techniques to understand whether the available factors can help explain startup outcomes.

## -> Dataset

The dataset used in this project is based on startup data from the **Big Startup Success/Fail Dataset from Crunchbase**, available on Kaggle.

For this project, the data was filtered to Indian startups with known outcomes. The final dataset contains **129 startups and 14 attributes**.

Some of the main information used in the analysis includes:

- Startup name
- Category
- Region and city
- Total funding
- Number of funding rounds
- Founding date
- First funding date
- Startup status

For this analysis:

- **Acquired / IPO** → Success
- **Closed** → Failure
- **Operating** → Excluded because the final outcome is not known

## -> Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Statsmodels
- Jupyter Notebook / Google Colab
- Git & GitHub

## -> Project Workflow

1. Problem Definition & Dataset Selection
2. Data Understanding
3. Data Cleaning & Data Quality Assessment
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Descriptive & Statistical Analysis
7. Sampling & Confidence Interval
8. Correlation Analysis
9. Hypothesis Testing
10. PCA & LDA
11. Simple & Multiple Linear Regression
12. Logistic Regression
13. Final Findings & Conclusion

## -> Main Analysis Performed

The project includes:

- Analysis of successful and failed startups
- Funding distribution analysis
- Missing value and outlier analysis
- Correlation between funding rounds and total funding
- Sampling and Central Limit Theorem
- 95% Confidence Interval
- Welch's t-test
- Chi-Square test
- Principal Component Analysis (PCA)
- Linear Discriminant Analysis (LDA)
- Simple Linear Regression
- Multiple Linear Regression
- Logistic Regression

## -> Key Findings

- Successful startups had higher observed mean and median funding than failed startups.
- The difference in mean funding was not statistically significant at the 5% level.
- Funding rounds showed a moderate positive relationship with total funding.
- Multiple regression explained more variation in total funding than simple regression.
- LDA and logistic regression showed that funding-related variables alone were not enough to clearly distinguish successful and failed startups.

## -> Repository Structure

```text
docs/
    project_definition.md

notebooks/
    01_startup_success_analysis.ipynb

reports/
    progress_log.md

README.md
```

## -> Project Status

**Analysis Completed**

The data analysis is complete. The project documentation, report, and GitHub repository are being finalized for submission.
