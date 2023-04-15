# Using Ingredients to Recommend Dishes

This project uses machine learning to recommend dishes based on a list of ingredients provided by the user. The project utilizes a dataset of over 200,000 recipes from [Kaggle](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions), which includes information on each recipe's name, ingredients, and other attributes.

###Project

The project recommends dishes based on a list of ingredients provided by the user. The dataset contains over 200,000 recipes, and the algorithm used is the cosine similarity algorithm. We transform the input ingredient list into a vector, normalize it, and calculate the cosine similarity with each recipe vector to generate a list of recommended dishes.
