# Capillary-ML-Hack
Capillary-ML-Hack, Analytics Vidhya

### Problem statement
Capillary Hackathon -  Recommender system for fashion retail.
Develop  an algorithm which will recommend best suited items from inventory to a user in order to improve his/her shopping experience. 

### Data description
![Alt Text](data_dictionary.png?raw=True "Data Dictionary")

### Libraries used 
* implicit 0.3.8 
* pandas 0.23.4
* scipy 1.2.0
* tqdm 4.29.1

####Final submission
User-Item matrix(R) was decomposed into lower dimensional user factors(U) and item factors(V). By randomly assigning the values in U & V, using alternating least squares iteratively U & V were computed such that we arrive closer to R = U x V. 

Then, using transaction data, last purchased item was taken for each of the users and top 10 items were recommended accordingly based on item-item similarity scores. 

####Other approaches tried
To be updated soon. 

### References
[1]https://medium.com/radon-dev/als-implicit-collaborative-filtering-5ed653ba39fe
