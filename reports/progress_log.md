# Project Progress

## 1. Project Setup & Dataset Selection

- Selected the project topic: **Data-Driven Analysis of Success and Failure Factors in Indian Startups**.
- Created the GitHub repository and organized the project files.
- Selected the startup dataset for the analysis.
- Defined startup outcomes:
  - **Closed** = Failure
  - **Acquired** = Success
  - **IPO** = Success
- Operating startups were not included because their final outcome is not known.

## 2. Problem Definition

- Defined the problem statement and objectives of the project.
- Decided the main questions to explore using the dataset.
- Defined the scope and limitations of the project.

## 3. Data Understanding

- Loaded the dataset using **Pandas**.
- Checked the number of rows and columns.
- Studied the columns and their data types.
- Viewed sample records from the dataset.
- Calculated basic descriptive statistics.
- Checked missing values in different columns.

## 4. Data Cleaning

- Checked the dataset for missing values.
- Handled missing categorical values where required.
- Converted funding data to numerical format.
- Checked for duplicate records.
- Checked numerical columns for outliers.
- Used the IQR method to examine funding outliers.
- Kept meaningful extreme funding values because they can represent genuinely highly funded startups.
- Converted the required date columns to datetime format.
- Created **Years_to_first_funding** for further analysis.

## 5. Exploratory Data Analysis

- Checked the number of successful and failed startups.
- Studied the distribution of startup funding.
- Compared funding of successful and failed startups.
- Studied funding rounds and geographical regions.
- Created different graphs such as histograms, box plots, bar charts, scatter plots and a correlation heatmap.
- Checked the relationship between funding rounds and total funding.

## 6. Statistical Analysis

- Calculated descriptive statistics for the main variables.
- Applied sampling and Central Limit Theorem concepts.
- Calculated a **95% confidence interval**.
- Performed correlation analysis.
- Used a **t-test** to compare funding of successful and failed startups.
- Used a **Chi-Square test** to check the relationship between region and startup outcome.
- Interpreted the results using p-values.

## 7. PCA and LDA

- Applied **PCA** on funding-related numerical variables.
- Checked the variance explained by the principal components.
- Applied **LDA** to study whether the selected variables could separate successful and failed startups.
- Checked the performance of LDA using cross-validation.

## 8. Regression Analysis

- Applied **Simple Linear Regression** to study funding rounds and total funding.
- Applied **Multiple Linear Regression** using funding rounds and years to first funding.
- Checked R², coefficients and p-values of the models.
- Applied **Logistic Regression** to study startup success and failure.
- Checked the accuracy and results of the logistic regression model.

## 9. Final Results

- Successful startups had higher average and median funding than failed startups.
- The t-test showed that the difference in mean funding was not statistically significant at the 5% level.
- Funding rounds had a positive relationship with total funding.
- Multiple regression explained more variation than simple regression.
- LDA and logistic regression showed that funding variables alone were not enough to clearly predict startup success or failure.
- Final conclusions and limitations were noted.

## Current Stage

**Project Analysis Completed**

The main analysis is complete. We are now finalizing the GitHub repository, project report and presentation for submission.
