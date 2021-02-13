# recommendation_system
My research paper- [Online Product Recommendation Engine.](https://ieeexplore.ieee.org/document/9231069)


***Abstract***

In this modern world, most of the products are brought through internet. So by using the recommendation technique we can improve our selling of the product. We have been provided with two csv files. The train.csv dataset contains the User ID, Invoice Number, Date and Time, Quantity, Country, Unit Price and Stock Code. By using these available parameters recommend the products to the customers. Previous work has used SVD algorithm or Matrix factorization for doing the recommendations.
In this paper we have used Restricted Boltzmann Machine (RBM) to decode the text into a latent vector sequence, especially for end-to-end collaborative filtering on the required task. For the task of recommending a stock id for each customer with the RBM model helps in yielding a model with significantly higher accuracy. Multi-task Learning is just used to improve the efficiency of learning through RBM which will give better predictions based on user and items it had purchased. This helps our model to recommend a stock code for the individual users based on the product they have already purchased. We have achieved a recommendation score of 94.4% to the customers with RBM method.
