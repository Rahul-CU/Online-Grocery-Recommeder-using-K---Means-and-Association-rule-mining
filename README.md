# Online-Grocery-Recommeder-using-K---Means-and-Association-rule-mining
How it works?

I have designed a product recommender model using K-means clustering and association rule mining which predicts and recommends the user the list of items they are most likely to purchase based on previous transactions and feedbacks of the grocery products. 

Product Recommender

I built a python script that takes in user_id, product_id, desired lift cutoff, and num_products to be returned to execute the product suggestions to be displayed on a product's website. 
It uses these inputs to determine the user's cluster (which is stored in a dataframe generated by the cluster analysis), filter the dataframe containing the product association rules for that cluster, and return the specified number of products with a lift greater than the lift input, prioritising the items with the greatest lift. If the number of products that fit the requirements is less than num_products, it will return all products that do.

