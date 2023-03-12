# auto-MPG_RegressionwithML


The aim of the project is to predict the attribute 'mpg' (miles per gallion) for various car models subject to various features like horsepower, weight, cylinders etc. The source of the dataset is https://archive.ics.uci.edu/ml/datasets/Auto+MPG. We have compared prediction results from three different algorithms - Linear regreassion, Boosted Decision Trees, and Random Forests. First, we show an exploitary data visualization to study correlation between several parametrs. It is evident that there is a strong strong multicollinerity in the dataset. We thus choose a Ridge regression model which is supposed to be more robust for such cases. 

The dataset has both numerical and categorical features, we have transfomed the categorical features using one-hot-encoders. And for all three methods, we have used grid-search CV method to obtain optimized hyparameters. In the end, it is found that the preformance of all three are very similar, with a RMSE loss funtion ~ 3. 
