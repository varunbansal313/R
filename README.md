# Data Analysis using R

This repository contains R scripts, datasets, and reports for data analysis projects, with documentation and comments to aid understanding.

## Exploratory Data Analysis

Analysing the Streaming Service data.

Dataset file name: Data_Centers.txt

Each row of the dataset represents information for each server gathered on December 1, 2022.

| Variable  | Description |
| ------------- | ------------- |
| Manufacturer | Name of the Manufacturer of the Server  |
| Server  | Server Model Number |
| DC  | Data Centre Name |
| SMBR  | Server Message Blocks Received |
| SMBT  | Server Message Blocks Transmitted |
| Conn  | Connections Made |

<br>


## Clustering

The data summarizes the expenses of randomly selected participants. Each column represents the percentage of income devoted to each expense category.<br>
We will use k-means clustering to segment these participants in to distinct clusters.

Dataset file name: Expense_Summary.txt

| Name | Description | 
| ------------- | ------------- |
| Food | Percentage of income spent on Food | 
| Enter | Percentage of income spent on Entertainment | 
| Edu | Percentage of income spent on Education | 
| Trans | Percentage of income spent on Transportation | 
| Work | Percentage of income spent on Work Related Expenses | 
| House | Percentage of income spent on Housing | 
| Oth | Percentage of income spent on Other Expenses |

<br>


## Multivariate Linear Regression

A major mail-order company tracks the time (in days) it takes for customers to receive their orders (each row in the dataset represents one order).<br>
We will use multiple linear regression to determine the factors which contribute to, and help predict, the delivery time (variable: DL). 

Dataset file name: Mail_Order_Delivery_Time.txt

| Variable | Description |
| ------------- | ------------- |
| DL | Time for delivery (in days, rounded to nearest 10th) |
| VN | Vintage of product (i.e. how long it has been in the warehouse). |
| PG | How many packages of product have been ordered |
| CS | How many orders the customer has made in the past |
| ML | Distance the order needs to be delivered (in km) |
| DM | Indicator for if the product is manufactured in Canada (C) or elsewhere (I) |
| HZ | Indicator for if the product is designated as Hazardous (H) or not (N). |
| CR | Indicator for which Carrier delivered the item (Def Post, or Sup Del) |
| WT | Weight of the shipment (in decagrams) |

<br>


## Classification

A major mail-order company tracks the time (in days) it takes for customers to receive their orders (each row in the dataset represents one order).<br>
The company has a goal of making all deliveries in at least 8.5 days. 
Any parcel delivered in at least 8.5 days is considered ‘On Time’ and anything after that is considered late.<br>
We will be to use a variety of classifiers to determine the factors which contribute to, and help predict, an ‘On Time’ delivery.

Dataset file name: Mail_Order_Delivery_Time.txt

| Variable | Description |
| ------------- | ------------- |
| DL | Time for delivery (in days, rounded to nearest 10th) |
| VN | Vintage of product (i.e. how long it has been in the warehouse). |
| PG | How many packages of product have been ordered |
| CS | How many orders the customer has made in the past |
| ML | Distance the order needs to be delivered (in km) |
| DM | Indicator for if the product is manufactured in Canada (C) or elsewhere (I) |
| HZ | Indicator for if the product is designated as Hazardous (H) or not (N). |
| CR | Indicator for which Carrier delivered the item (Def Post, or Sup Del) |
| WT | Weight of the shipment (in decagrams) |



