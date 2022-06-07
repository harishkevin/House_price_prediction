#Predictive analysis on house price in California.

Overview: A regression model to predict the price of house price in california based on features such as longitude,latitude, housing_median_age,	total_rooms	total_bedrooms, population,	households,	median_income,	ocean_proximity,	rooms_per_household,	population_per_household. The model is built with randomforestregressor and done variuos hyperparameter tuning.

Phases of Work: 
1. The data is downloaded from kaggle.
2. Then the test and training set is seperated(80% training set and 20%test set)
3. Data is visualized to get the insights and to find any correlations.
4. Data is cleaned and the text attributes are encoded.
5. Feature scaling is done for the algorithm to run efficiently.
6. The training data is trained with the various algorithms such as linear regression, decision tree, random forest.
7. The random forest showed a promising results.
8. Fine tuning the model with hyperparameter tuning using gridsearch CV
9. Evaluated the test set

Metrics for Evaluating: Root mean squared erroer is used to evaluate. The model returned 67% acuracy which is very low, since this ,odel is not regularized. 
