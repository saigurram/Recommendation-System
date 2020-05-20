# Recommendation-System
Amazon ratings recommendation system

![alt text](https://miro.medium.com/max/1200/1*QbBtk_xjwQWDW7aCrmGwfw.jpeg)

# Define 

Amazon, Netflix and a lot of organizations are currently relying on Recommendation systems to suggest products to a user.

Recommendation systems can be based on content, item/user based and model based.

Content based recommendation systems rely on analyzing the content and suggesting products that have similar content. The major drawback is only products that are very similar to each other are recommended.

User based recommendation systems rely on understanding how one user is similar to the other based on the product ratings/products viewed etc. Major drawback is often users tend to change their opinions and if the user is new to the product then there is no data to support the recommendations.

Item based recommendation systems rely on understanding how one item/product is related to the other. Based on their porpularity, rating etc. Major drawback is not all items have ratings and if the product is new then there is no data to support the recommendations.

Model based recommendation systems rely on matrix factorization approach where all the relationships between users and items are condensed and converted into two separate vectors. This approach resolves the issues of user based and item based recommendation systems.

# Objective 

Create a model based recommendation system. 

# Dataset

The Amazon beauty ratings dataset can be obtained from Kaggle - https://www.kaggle.com/skillsmuggler/amazon-ratings?select=ratings_Beauty.csv

Dataset consists of Userid's, Ratings, Product id and timestamp. Dataset contains more than 2M records.

# Data Exploration & Model 

Used cosine similarity to calculate the similarity between products. 

Used SVD(Singular Value Decomposition) and Pearson Correlation to calculate similarity between both users and products. 

# Summary 

The model based recommendation system can now be used to recommend products. 
The sparsity and scalability issue of user based/item based systems has been resolved in model based system. 






