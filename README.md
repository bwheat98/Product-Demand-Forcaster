# Product-Demand-Forcaster
In this project we look at product demand forcasting. We are using a dataset that contains a date, product code, warehouse, product_category, and order_demand. This dataset can be downloaded here https://www.kaggle.com/felixzhao/productdemandforecasting. we will look at ways of adding value to the dataset through feature engineering. Then will use a couple different models to forcast the demand for a particular product.

To forcast product demand there are 3 methods you can call. Probably the best one to call is dailyprophetForcast(prod_code) where prod_code is a string correlating to a product code from the dataset. Another option is ARIMAdailyForcast(prod_code) for daily forcasting and monthlyArimaForcast(prod_code) for monthly forcasting.
