# Houses-to-rent
This dataset has 10692 houses for rent with 13 different classes / This dataset contains 10692 houses to rent with 13 different features( 13 columns x 10692 rows).
Some features I can specify: city, area, rooms, rent amount.
I will try to choose a model that can predict well rent amount( target) based on the dataset I have.
For the beginning I plot the target with seaborn lib from Python, to explore the target from the dataset.
Because rent amount is a continue value, I diceded to choose some regression estimators for this dataset like: RandomForestRegressor,LinearRegression,DecisionTreeRegressor(), SVM,  Neural_network. 
I applied some feature engineering to my datasets like the scale of the features and the importance of the feature. The purpose was to improve the performance of the regression estimators with the new dataset that I have obtained after feature engineering.
After that exploration, I decided to fir MLPRegressor, and predict rent amount values based on the test dataset. Also, I obtained a score = 0.8837, a good estimation!



![Opera Snapshot_2022-02-22_120011_github com](https://user-images.githubusercontent.com/30430563/155109082-67f27e1c-3c80-4e33-ab15-7131e1ce3b00.png)

![Opera Snapshot_2022-02-22_120011_github com](https://user-images.githubusercontent.com/30430563/155116374-603e19e4-d83b-460c-88ab-a1a433341505.png)


![Opera Snapshot_2022-02-22_124306_github com](https://user-images.githubusercontent.com/30430563/155116411-c8ef8856-951d-40b1-9c0f-5b3401eb0a79.png)
