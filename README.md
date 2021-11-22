# Houses-to-rent
This dataset has 10692 houses for rent with 13 different classes / This dataset contains 10692 houses to rent with 13 different features( 13 columns x 10692 rows).
Some features I can specify: city, area, rooms, rent amount.
I will try to choose a model that can predict well rent amount( target) based on the dataset I have.
For the beginning I plot the target with seaborn lib from Python, to explore the target from the dataset.
Because rent amount is a continue value, I diceded to choose some regression estimators for this dataset like: RandomForestRegressor,LinearRegression,DecisionTreeRegressor(), SVM,  Neural_network. 
I applied some feature engineering to my datasets like the scale of the features and the importance of the feature. The purpose was to improve the performance of the regression estimators with the new dataset that I have obtained after feature engineering.
After that exploration, I decided to fir MLPRegressor, and predict rent amount values based on the test dataset. Also, I obtained a score = 0.8837, a good estimation!







