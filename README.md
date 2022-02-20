## Project Description
The goal of the project is to understand how discount rates could affect the profit margin for online retail orders. We worked with a 
[dataset](https://www.kaggle.com/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis) about a online retailer's database. 


## Project Details
The project was carried out in the following steps:

+ Identify features that may be related to profit, only information that can be realised before shipment can be included in the features
+ Build a simple binary classification model to identify loss making orders
+ Build a 3 class classification model to identify high profit orders and loss making orders, with discount rate as the key input feature
+ Adjust discount rates for those orders with low predicted profits and compute the expected gain in profit acheived by the model (taking into account of the model's performance)
