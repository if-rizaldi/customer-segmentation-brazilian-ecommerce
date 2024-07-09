# BRAZILIAN E-COMMERCE CUSTOMER SEGMENTATION
Data source : [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data)

## OVERVIEW

This project focuses on analyzing the Brazilian E-Commerce Public Dataset by Olist from 2016 to 2018. Through the application of the RFM (Recency, Frequency, Monetary) model, we aim to segment customers based on their transaction behaviors. This segmentation will enable us to gain insights into customer preferences, behavior patterns, and potential marketing strategies tailored to different customer segments.

### About the Dataset

The Brazilian E-Commerce Public Dataset by Olist includes information about 100,000 orders made between 2016 and 2018 across multiple marketplaces in Brazil. The dataset provides various dimensions for each order, such as:

* Order Status
* Price
* Payment and Freight Performance
* Customer Location
* Product Attributes
* Customer Reviews

Additionally, there is a geolocation dataset linking Brazilian zip codes to latitude and longitude coordinates. This comprehensive dataset allows for a detailed analysis of the e-commerce activities within Brazil during the given period.
Business in Brazil

E-commerce in Brazil has seen significant growth, driven by increasing internet penetration and a growing middle class with greater purchasing power. The period from 2016 to 2018 saw substantial developments in the e-commerce sector, with more consumers embracing online shopping for convenience and a wider range of products. The rise of marketplaces like Olist, which connect small businesses to broader markets, has further fueled this growth.

### Market Development in Brazil (2016-2018)

During this time, Brazil experienced notable advancements in its digital infrastructure, contributing to the expansion of online retail. The e-commerce market grew rapidly, with more businesses adopting online channels and customers becoming more comfortable with online transactions. Key trends included the increasing use of mobile devices for shopping, the importance of logistics and delivery services, and the influence of customer reviews on purchasing decisions.

### Importance of Market Segmentation for Targeted Marketing

Understanding market segmentation is crucial for targeted marketing as it allows businesses to tailor their strategies to different customer groups. By segmenting the market, companies can create personalized marketing campaigns, improve customer satisfaction, and ultimately increase sales. In the context of the Olist dataset, segmentation can help identify distinct customer groups based on their purchasing behavior, enabling Olist and its partners to enhance their marketing efforts and customer relationships.

## GOALS

The primary goal of this analysis is to understand market segmentation using the RFM (Recency, Frequency, Monetary) model. The analysis aims to categorize customers into four distinct groups:

1. **Best Customers**: Customers who have transacted recently, frequently, and spend more than others.
2. **High-spending New Customers**: Customers who have transacted only once, very recently, and spent a lot.
3. **Lowest-Spending Active Loyal Customers**: Customers who have transacted recently and frequently but spend the least.
4. **Churned Best Customers**: Customers who used to transact frequently and spend a lot but haven’t transacted in a long time.

### RFM Model Explained

The RFM model is a marketing analysis tool used to identify a company's best customers by examining three main factors:

* **Recency**: How recently a customer made a purchase.
* **Frequency**: How often a customer makes a purchase.
* **Monetary**: How much money a customer spends on purchases.

By analyzing these factors, businesses can segment their customers into different groups based on their buying behavior. This segmentation helps in creating targeted marketing strategies, improving customer retention, and enhancing overall sales performance.
Objective

The objective of this analysis is to use the RFM model to segment customers into the aforementioned groups. By understanding these segments, the company can develop tailored communication strategies to enhance customer engagement and increase sales. The specific goals include:

* Identifying the most valuable customers.
* Recognizing high-potential new customers.
* Understanding the behavior of loyal but low-spending customers.
* Detecting previously valuable customers who may have churned.

This segmentation will provide insights into customer behavior and enable Olist to optimize its marketing efforts for better customer satisfaction and business growth.

### Analysis 
As Data Scientists working on the Brazilian E-Commerce Public Dataset by Olist, we will segment customers based on recency, frequency, and monetary value using the K-Means clustering method. The evaluation metric used will be the elbow method to determine the optimal number of clusters. The elbow method evaluates the model by plotting the within-cluster sum of squares (WCSS) against the number of clusters, with the 'elbow point' indicating the ideal number of clusters. By accurately segmenting customers, we can implement tailored business strategies for each customer segment, minimizing wasted resources and maximizing marketing effectiveness.

## RESULT

In this analysis of the Olist dataset, our primary goal was to gain insights into customer segmentation using recency, frequency, and monetary (RFM) scores. The dataset provided a comprehensive view of customer transactions, including order details, payment information, and customer reviews, spanning the years 2016 to 2018. Our initial exploration revealed a diverse customer base across different regions of Brazil, with São Paulo (SP) being the most predominant state, followed by Rio de Janeiro (RJ) and Minas Gerais (MG).

Our analysis revealed distinct customer segments based on transaction behaviors. Notably, we identified 1079 High-spending New Customers, 84 Lowest-Spending Active Loyal Customers, and 29 Best Customers. Interestingly, we found no instances of Churned Best Customers, likely due to the dataset's limited two-year timeframe. This segmentation highlights opportunities for targeted marketing strategies aimed at increasing engagement and spending among various customer segments.



