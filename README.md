"# Recommender_Systems_Amazon" 

Using a deep learning architecture, we implemented a model that can estimate a user's interest in a specific item. With this model, we can generate a list of items to recommend to the user that they have not purchased yet, but according to the patterns the model has found between users and items, they are likely to enjoy and rate highly. The dataset for this project includes real data related to electronic products available on the online store Amazon.

Although this project deals with online store data, this recommender model can be applied to various domains. For example, a similar system can be designed to recommend movies or music tracks to users.

The training data is located in the file amazon_train.csv. This file contains 4 columns, which respectively represent the user ID, product ID, the rating given by the user to the product, and the timestamp of the rating. The network I implemented takes the numerical IDs of the user and the product as input and predicts the rating that the user would give to that product.
