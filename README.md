 # A NON-STORE ONLINE BUSINESS RECOMMENDER SYSTEM
 
 
 # INTRODUCTION
 ---
 A non-store online retail business is an e-commerce venture that operates entirely in the digital space without any physical locations. These businesses provide their services through websites and applications, allowing customers to place orders online and have products shipped directly to their homes. The popularity of such businesses has surged, especially since the COVID-19 pandemic. Lockdowns and social distancing measures prompted consumers to seek safer and more convenient shopping options, making non-store online retailers essential by offering a wide range of products and services accessible from home. Advantages of these online retailers include a broad selection of goods, shopping privacy, avoidance of long lines, access to unique and rare items, detailed product information, and online discounts. To maximize these benefits, businesses can use recommendation systems, which are information filtering tools designed to predict user preferences and provide personalized suggestions.
 
 
 # PROBLEM STATEMENT
 ---
 Non-store online retail businesses encounter various challenges that need to be addressed to thrive in the digital marketplace. These challenges include customer engagement, product discovery, personalization, and inventory management. The processes involved can be cumbersome, requiring the collection of information on customer preferences, item costs, product quality, durability, and other factors. Often, retailers struggle to gather this information, which can negatively affect their business. A UK-based online retail company, specializing in unique all-occasion gifts and serving both individual customers and wholesalers, recognizes the importance of a recommendation system to overcome these challenges and enhance customer experience.

Among the several factors, our primary objectives are:

* Enhancing customer engagement by offering personalized product recommendations based on user preferences and purchase history.

* Mitigating the product discovery challenge by highlighting relevant items, making the shopping experience more enjoyable and efficient.



# DATA UNDERTANDING 
---
We will utilize the dataset from the UCI Machine Learning Repository, which includes transactions from 2010 to 2011 for a UK-based and registered non-store online shop specializing in unique gifts.

Description of Columns:

The dataset contains the following 8 columns:

*  ' InvoiceNO'-Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

* 'StockCode'- Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

* 'Description'-Product (item) name. Nominal.

* 'Quantity'- The quantities of each product (item) per transaction. Numeric.

* 'InvoiceDate'- Invoice Date and time. Numeric, the day and time when each transaction was generated.

* 'UnitPrice ' - Unit price. Numeric, Product price per unit in sterling.

* 'CustomerID' - Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

* 'Country' -  Country name. Nominal, the name of the country where each customer resides.


# DATA CLEANING
---
Performed the following data-cleaning processes:

* Imported the data.

* Changed the date type.

* Removed duplicate values.

* Eliminated outliers in the Unit Price and Quantity columns.

* Dropped all null values in the dataset.



# EXPLORATORY DATA ANALYSIS
---
* Univariate Analysis

* Bivariate Analysis

* Multivariate Analysis



# MODELLING 
---

I utilized the following regression models:

*  Memory-Based Model using Cosine and Pearson Similarity

*  Collaborative Filtering using the Surprise Library

*  Evaluation Metric: RMSE



# CONCLUSION
---
* The best time to offer discounts to customers is in November, as it has the highest sales volume.


* The optimal time for advertising is in the afternoon, which is when most purchases are made.


* The quantity of orders is not influenced by the price of an item, as there is no correlation between quantity and price.


* Thursdays and Sundays are the days with the highest purchase quantities.


* The KNN (K-Nearest Neighbors) With Means model has a test RMSE value of 0.244 and a cross-validation RMSE value of 0.246.


* The white hanging light holder has the highest number of orders, whereas the pack of 72 retrosport cakes has the fewest orders.




# RECOMMENDATION 
---
 The developed recommendation system will significantly benefit customers and e-commerce companies by providing personalized product suggestions based on user preferences and purchase history. It also addresses the product discovery challenge by highlighting relevant items, enhancing the shopping experience's enjoyment and efficiency. However, the recommendation engine can be further improved by utilizing deep learning techniques and deep hybrid model-based recommendations, integrating various neural building blocks to create more powerful and expressive models.
