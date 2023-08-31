# Customer_Churn_Prediction

To develop a predictive framework for enabling proactive retention strategy for a Telecom company.

Outliers were treated by capping extreme values and feature with same values for most of observations
means they have zero variance, such features were removed.

Conducted univariate and bivariate analysis to establish to derive insights and those features like 
gender, phone service which had least effect on churning(target variable) and k-best features were
selected.

Various models were tested including Random Forest Classifier and Gradient Boosting Classifier and '
evaluated with confusion matrix for various metrics.
Lorentz curve was plotted for cumulative effect of variables contributing to model performance and 
top 10 variables were observed through ranking.
Top 30% gives 78% of Prediction.Tenure and total charges were the top features.Hence top 30% are more likely to churn.
