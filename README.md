# all_regression_models
Tried Linear Regression, KNN Regressor, Decision Tree Regressor and Random Forest Regressor, Support Vector Regressor 
in same dataset.

In ridge-lasso-regression repository where I applied linear regression along with ridge and lasso, we saw that 
the highest accuracy we are getting with test dataset is 43.113%, so I tried applying three other regression models
- KNN Regressor
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor

PROBLEM STATEMENT

1. Check the dataset if it needs cleaning.
2. Check the dataset if it needs missing value treatment.
3. Check the dataset if it needs scaling.
4. Split data into training data and testing data.
5. Create a linear regression model to predict profit depending on various independent feature.
6. Check the accuracy of your model.
7. Apply other regression models and check which one is giving best accuracy.

STEPS FOLLOWED

1. Importing required libraries.
2. Loading dataset.
3. Check first five rows of the dataset.
4. Creating a copy of the dataset.
5. Statistical info about dataset.
6. Getting information on dataset.
7. Encoding dataset.
8. Scaling the Dataset. I have used (standard scaler).
9. Splitting data into training set and testing set.
10. Importing five regression models (Linear Regression, KNN Regressor, Decision Tree Regressor, Random Forest Regressor
    and Support Vector Regressor.
12. Making objects of each model and creating a list of  the objects.
13. Iterating through the models list, fitting training data in each model one by one.
14. Making predictions with test data using each model one by one.
15. Checking accuracy of each model one by one.

CONCLUTION

In ridge-lasso-regression repository where we applied linear regression along with ridge and lasso, we saw that 
the highest accuracy we are getting with test dataset is 43.113%

So here we can conclude that Random Forest Regressor is giving the highest accuracy with test data.

So here we can conclude that Random Forest Regressor is giving the highest accuracy with test data.
