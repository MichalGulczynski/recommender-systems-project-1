The project was carried out as part of the "recommender systems" class. 
The goal of the project is to create a recommender that achieves better results than amazon's recommender of a few years ago. 
The first step is data preparation. As part of the preparation, we perform operations such as aggregation and mapping, for example. 
The next step is to prepare user features and items. In the case of describing users, I chose to describe the probability of occurrences of given features calculated from previous operations. In the case of items, it describes the occurrence of specific features using one-hot encoding. 

The extracted user and item feature descriptions are passed to the fit methods, where the recommender is trained, and the recommend method where it returns the most matching recommendations. 
Of the available recommender types, I chose Linear Regression Recommender because of its speed and relatively high performance. 

Finally, tuning of the recommender and final evaluation of the results is performed. 
