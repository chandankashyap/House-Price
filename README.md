# House-Price

Here is my solution to the House Price data set.
I have tried to make the solution as detailed as possible.

The key highlights are as follows:

1.	Data Exploration/Visualization

2.	Outlier Treatment

3.	Feature Engineering

  •	Imputing missing values by proceeding sequentially through the data

  •	Transforming - numerical variables that are categorical

  •	Label Encoding

  •	Scaling (using RobustScaler) along with Pipelines

  •	Box Cox Transformation of skewed features 

  •	np.log1p transformation

  •	Getting dummy variables for categorical features.


4.	Feature Importance/Selection

  •	Lasso Regression

  •	Select k best

  •	feature_importances_ using Decision Trees


5.	Splitting Data
  
  •	Train test split 

  •	Grid search CV


6.	Regression Models Used (Care was taken to ensure no chances of Overfitting)

  •	Lasso Regression - RMSE =  0.11; R squared =  0.91

  •	Ridge Regression - RMSE =  0.11; R squared =  0.91

  •	Decision Trees - RMSE =  0.18; R squared =  0.78

  •	Random Forest - RMSE =  0.14; R squared =  0.87

  •	Gradient boost - RMSE =  0.11; R squared =  0.91

  •	Adaboost - RMSE =  0.13; R squared =  0.88


7.	Hyper-Parameter Tuning of all models


8.	Analyse Model performance

  •	RMSE

  •	R squares


9.	Finally predicting the Label of Test data using Gradient Boosting Regressor

Suggestions are always welcome. 
