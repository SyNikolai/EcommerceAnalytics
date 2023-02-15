# EcommerceAnalytics
A deep dive into annual transactions of an online retail shop.

## Introduction

The following analysis is based upon a sales transaction data set of UK-based e-commerce (online retail) for one year(_source:https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business_). This London-based shop has been selling gifts and homewares for adults and children through the website since 2007. Their customers come from all over the world and usually make direct purchases for themselves. There are also small businesses that buy in bulk and sell to other customers through retail outlet channels.

The dataset contains __500K rows__ and __8 columns__. The following is the description of each column.

 1) __TransactionNo__ (categorical): a six-digit unique number that defines each transaction. (_The letter “C” in the code indicates a cancellation_).

 2) __Date__ (numeric): the date when each transaction was generated.

 3) __ProductNo__ (categorical): a five or six-digit unique character used to identify a specific product.

 4) __Product__ (categorical): product/item name.

 5) __Price__ (numeric): the price of each product per unit in pound sterling (£).

 6) __Quantity__ (numeric): the quantity of each product per transaction. (_Negative values indicate cancelled transactions_).

 7) __CustomerNo__ (categorical): a five-digit unique number that defines each customer.

 8) __Country__ (categorical): name of the country where the customer resides.

There is a small percentage of __order cancellation__ in the data set. Most of these cancellations were due to out-of-stock conditions on some products. Under this situation, customers tend to cancel an order as they want all products delivered all at once.

## Analysis overview - Research outcomes

Transaction data analysis is a process of examining and interpreting data collected from customer transactions in order to gain insights and make informed business decisions. For an e-commerce business, analyzing transaction data over the course of a year can help in several departments.

Given the scope of the data features provided in this dataset, we will focus our attention in the following:

-  Identifying sales patterns / distribution of transactions and revenue over time,

-  Understanding the demographics and purchasing habits of the customers,

-  Insights concering product popularity/profitability,

-  Customer retention.


Overall, analyzing transaction data can provide valuable insights that can help an e-commerce business make data-driven decisions to improve its performance.

## What can you find in this notebook

In order to achieve the goals of our research, a wide variety of metrics and visualisations have been used. The outline of the analytics process can be summed up in the following 4 steps:

1) **Importing, cleaning and validating the data**

2) **Exploratory analysis - Understanding the data**

3) **Market Basket Analysis**

4) **Cohort Analysis**




