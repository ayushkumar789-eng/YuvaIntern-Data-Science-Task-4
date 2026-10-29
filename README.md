# YuvaIntern-Data-Science-Task-4
# Supervised Learning: Retail Sales Prediction

## Project Overview
This project implements a supervised machine learning regression model using Python and Scikit-learn. It uses the cleaned Online Retail dataset to explore whether transaction date-related features can predict retail sales values.

The project demonstrates data preparation, feature engineering, model training, cross-validation, evaluation, and performance analysis.

## Internship Details
- **Internship:** Virtual Data Science with Python
- **Platform:** YuvaIntern
- **Task:** Week 4 — Supervised Learning Model Implementation
- **Author:** Ayush Kumar

## Objective
To design and implement a supervised learning model using a publicly available dataset and evaluate its predictive performance using appropriate validation techniques and regression metrics.

## Problem Statement
Predict the transaction sales value (`TotalSales`) using date-derived features from the Online Retail dataset.

**Learning Type:** Supervised Learning  
**Problem Type:** Regression  
**Algorithm:** Linear Regression

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Import the required Python libraries.
2. Load and inspect the cleaned dataset.
3. Check missing values and duplicate records.
4. Prepare the data and create the target variable when necessary.
5. Perform feature engineering using transaction dates.
6. Select input features and the target variable.
7. Split the data into training and testing sets.
8. Train a Linear Regression model.
9. Evaluate the model using MAE, RMSE, and R².
10. Perform five-fold cross-validation.
11. Analyze model coefficients, strengths, and limitations.

## Dataset
**Dataset:** Online Retail  
**Source:** UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/352/online+retail

The project uses the cleaned dataset `online_retail_cleaned.csv` prepared in the previous task.

## Evaluation Metrics
- **Mean Absolute Error (MAE):** Measures the average absolute prediction error.
- **Root Mean Squared Error (RMSE):** Penalizes larger prediction errors more heavily.
- **R-squared (R²):** Measures the proportion of target variance explained by the model.
- **Cross-Validation MAE:** Helps assess model performance across different training-data folds.

## Results
The actual evaluation metrics should be recorded after executing the notebook. No performance values are assumed in advance.

**Important limitation:** The current baseline uses date-derived features only. These features may not contain enough information to predict transaction sales accurately. The model's performance should therefore be interpreted alongside the evaluation metrics and limitations.

## Strengths
- Implements a complete baseline regression workflow.
- Uses a separate test dataset for evaluation.
- Integrates feature scaling and regression into a Scikit-learn pipeline.
- Uses cross-validation to examine performance stability.
- Produces interpretable model coefficients.

## Limitations
- Date-derived features alone may have limited predictive power.
- Linear Regression may not capture complex relationships in retail transactions.
- Performance depends on the dataset and selected features.
- Historical patterns may not generalize to future transactions.

## Future Improvements
- Engineer additional features that are available at prediction time.
- Compare Linear Regression with other regression algorithms.
- Investigate prediction errors and potential outliers.
- Use appropriate cross-validation and hyperparameter tuning.
- Evaluate the final model on relevant unseen data.

## Project Files
- `Task4_Supervised_Learning.ipynb` — notebook containing data preparation, feature engineering, model training, evaluation, and visualizations.
- `online_retail_cleaned.csv` — cleaned dataset, if included in the repository.
- `Ayush_Kumar_YuvaIntern_Task4_Report.docx` — detailed project report, once finalized and uploaded.

## Conclusion
This project demonstrates the implementation of a supervised learning regression workflow using Python and Scikit-learn. It covers preprocessing, feature engineering, training, cross-validation, and evaluation. The actual model metrics will determine how effectively the selected features predict retail sales and what improvements are needed.

## References
- [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
