Titanic Survival Prediction
This project applies Machine Learning algorithms to predict the survival of passengers on the Titanic. The dataset comes from the well-known Kaggle Titanic Challenge.
The project demonstrates data preprocessing, feature engineering, model training, evaluation, and model comparison using multiple algorithms.
 Project Structure
Titanic-Survival-Prediction
│-- data                # Dataset files
│-- notebooks           # Jupyter Notebook with analysis
│-- models             # Trained models
│-- README.md            # Project documentation
│-- requirements.txt     # Dependencies
Technologies Used
•	Python 3
•	Pandas – data manipulation
•	NumPy – numerical operations
•	Matplotlib & Seaborn – visualization
•	Scikit-learn – machine learning models
•	XGBoost – advanced boosting algorithm

 Steps in the Project
1.	Data Preprocessing
o	Handling missing values
o	Encoding categorical features
o	Feature scaling & transformation
2.	Exploratory Data Analysis (EDA)
o	Visualizing survival distribution
o	Correlation analysis
o	Feature engineering (e.g., Title extraction from names)
3.	Model Training
o	Logistic Regression
o	Decision Tree
o	Random Forest
o	XGBoost
4.	Model Evaluation
o	Accuracy, Precision, Recall, F1-score
o	ROC-AUC Score
o	Confusion Matrices

Results
Model	Accuracy	Precision	Recall	F1-score	ROC-AUC
Logistic Regression	0.801	0.752	0.697	0.722	0.780
Decision Tree	0.763	0.680	0.698	0.689	0.750
Random Forest	0.799	0.743	0.720	0.730	0.783
XGBoost	0.802	0.758	0.701	0.727	0.782

Final Model Chosen: 
•	Random Forest – due to the best balance of Precision, Recall, and F1-score.
•	XGBoost also performed competitively and is a good alternative.

