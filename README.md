# Ingredient-Based Dish Recommendation

This project utilizes machine learning to recommend dishes based on a list of ingredients provided by the user. It leverages a dataset of over 200,000 recipes from [Kaggle](https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions) which includes recipe names, ingredients, and other attributes.

## How It Works

1. **Ingredient Input**: The user provides a list of ingredients.
2. **Vector Transformation**: The input ingredient list is converted into a vector representation.
3. **Cosine Similarity**: We compute the cosine similarity between the user’s ingredient vector and vectors for each recipe in the dataset.
4. **Recommendation**: Recipes with the highest cosine similarity scores are recommended to the user.

## What is Cosine Similarity?

Cosine similarity is a metric used to measure how similar two vectors are. It is defined as the cosine of the angle between two non-zero vectors, which provides a measure of their orientation rather than their magnitude. In the context of this project, it helps identify recipes that closely match the user's input ingredients based on their vector representations.

## How to Run

1. Clone the repository and set up the environment.
2. Load the dataset and preprocess the recipe data.
3. Implement the cosine similarity algorithm to generate dish recommendations based on the input ingredients.

## Conclusion

This project demonstrates the use of cosine similarity for recommending dishes, providing users with tailored recipe suggestions based on their ingredient preferences.
