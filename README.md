# Consumer-Behavior-Prediction
The main objective of this project is to train a predictive model which will allow the company to maximize the profit of its next marketing campaign. A response model can provide a significant boost to the efficiency of a marketing campaign by increasing responses as well as reducing expenses. Therefore, this project is designed to predict who will respond to an offer for a product or service.

- Following are the descriptions of the variables in this dataset:
     Kidhome: Number of small children in customer’s household.
     Teenhome: Number of teenagers in customer’s household.
     Income: Customer’s yearly household income.
     MntFishProducts: Amount spent on fish products in the last 2 years.
     MntMeatProducts: Amount spent on meat products in the last 2 years.
     MntFruits: Amount spent on fruits products in the last 2 years.
     MntSweetProducts: Amount spent on sweet products in the last 2 years.
     MntWines: Amount spent on wine products in the last 2 years.
     MntGoldProds: Amount spent on gold products in the last 2 years.
     NumDealsPurchases: Number of purchases made with a discount.
     NumCatalogPurchases: Number of purchases made using catalog.
     NumStorePurchases: Number of purchases made directly in stores.
     NumWebPurchases: Number of purchases made through the company’s website.
     NumWebVisitsMonth: Number of visits to the company’s website in the last month.
     Recency: Number of days since the last purchase.

- Conclusions:
    In conclusion, the predicted results are better than what we thought, especially SVMs work very well on our dataset. What we did not expect is the original dataset, which without features selections, got the higher predictive results. In this case, SVMs works better than the logistic regression model. In the future, we could try cross-validation to get the average accuracies under these two models and to see how the accuracies change over time.
