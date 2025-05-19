This project analyzes student performance data to understand how different factors like gender, race, parental education level, lunch type, and test preparation affect student scores in math, reading, and writing.

What I Did
1.Cleaned and prepared the data for analysis

2. Performed Exploratory Data Analysis (EDA) to explore trends and patterns
   
3. Created a new column called “Total Score” by adding math, reading, and writing scores
   
4. Trained machine learning models (Linear Regression, Lasso, and Ridge) to predict the total score
 
5. Tested the models and evaluated their performance
   
6. Compared models using metrics like RMSE, MAE, and R² Score

Key Findings
Linear Regression showed perfect results with R² = 1.0 on both training and test sets, which might be a sign of overfitting or data leakage.

Lasso and Ridge also performed well with very small errors.

Overall, the models were able to predict total scores very accurately.

Tools Used
Python

Pandas

Matplotlib & Seaborn (for visualization)
Scikit-learn (for model training)
