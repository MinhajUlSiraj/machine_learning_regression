Machine Learning Specialization - Regression
This repository contains my practical implementations of various Regression models as part of the "Machine Learning A-Z" course on Udemy. It includes hands-on practice with multiple algorithms using Python, focusing on data preprocessing, model building, and evaluation.

📁 Repository Structure
📓 Jupyter Notebooks
Simple Linear Regression: Predicting a dependent variable based on a single independent variable (e.g., Salary vs. Years of Experience).

Multiple Linear Regression: Handling multiple independent variables and managing categorical data using One-Hot Encoding.

Polynomial Regression: Modeling non-linear relationships by transforming features into polynomial terms.

Support Vector Regression (SVR): Implementing SVR with Feature Scaling to handle non-linear data points.

Decision Tree Regression: A non-linear, non-continuous model that splits data into different nodes.

Random Forest Regression: An ensemble learning method that uses multiple decision trees for improved accuracy.

📊 Datasets
Salary_Data.csv: Used for Simple Linear Regression.

50_Startups.csv: Used for Multiple Linear Regression (includes features like R&D Spend, Administration, and Marketing Spend).

Position_Salaries.csv: Used for non-linear regression models (Polynomial, SVR, Decision Tree, and Random Forest).

🛠️ Tools & Libraries
The following Python libraries were utilized across the projects:

NumPy: For mathematical operations and array handling.

Pandas: For data manipulation and analysis.

Matplotlib: For data visualization and plotting regression results.

Scikit-Learn: For implementing machine learning models and preprocessing (LabelEncoding, OneHotEncoding, Feature Scaling).

💡 Key Learnings
Data Preprocessing: Importance of handling missing values, encoding categorical data, and splitting datasets into Training and Test sets.

Feature Scaling: Essential for models like SVR where the distance between data points matters.

Model Selection: Understanding which regression model to apply based on the nature of the dataset (linear vs. non-linear).

Evaluation: Visualizing results to compare predicted values against actual data points.
