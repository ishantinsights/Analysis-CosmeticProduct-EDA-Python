# Analysis-CosmeticProduct-EDA-Python


## Overview
- Cleaned the data using python library which is Pandas and numpy
- Performed EDA with the help of numpy, pandas, Matplotlib andseaborn


## Problem Statement
One of India's top most cosmetic product company has a wide range of
sales spread across different parts of the country. The given data is the sales record of
approximately 3 years . Analyze the data for some good actionable insights which can
increase their demand planning, warehouse planning, pricing of products which in turn
can increase their revenue.

## Data sets
● ParentSKU: Parent Stock Keeping Unit.
● Site ID: Location of Warehouse.
● Year: Year on which sales had happened.
● Month: Monthon which sales had happened.
● CategoryNameID: Product Category Name ID.
● Unit: Unit of the product package.
● Qty: Number of products sold.
● Net Sales Calculated: Total amount that should be billed.
● Cash Discount: Per product discount on purchase of bulk.
● Amount to customer: Amount that the customer has been billed.
● MRP: Maximum Retail Price of the product.
● Pack Size: Quantity of per product that has been bought.
● Pack Unit: Unit of the product.
● State: State at which the sales had happened.
● Zone: Zone ID where the sales had happened.
● Master Category: Master Category of the product. Super set of
Category Name ID.
● Size: Pack size of the product.
● Rank: Priority of the product to the client. Rank 1 is more important
and so on..
● Date: Transaction date.

## Insights
1. DELMDK warehouse has highest net sales 
2. DEHRADHUN, KOCHI, PATNA, RAIPUR, RANCHI, BHUBANESWAR, VIJAYAWADA, JAMMU, SECUNDRBAD, CHENNAI,GUWATHATI, INDORE, JAIPUR, KOLKATA where sales are very low
3. Discounted items are very less
4. Sales has zonal effect as we can see that south and east zone have less sales than west and north
5. 30gm, 1kit, 150ml,100ml product size has high sales
6. There is comparatively high sales on june, August, januaury and december(seasonality)
7. Winter and rainy season is where customer are more interested in buying the product
8. Product with id F0033, F0034, F0089, F0094, F0098,F0099,F0306 has the highest sales we can promote this products in the warehouse and zones where there are less sales 
9. Using category 7 and 6 products in zones and warehouse where there are less sales
10. product which has high sales have comparatively low price and low MRP has high price 
11. The category with low MRP i.e 7 and 6 has comparatively high sales 

## Solution
1. We could try to increase our sales in south and east by giving more discount in MRP
2. 30gm, 1kit, 150ml,100ml product sizes we can Promote this product in south and east or in DEHRADHUN, KOCHI, PATNA, RAIPUR, RANCHI, BHUBANESWAR, VIJAYAWADA, JAMMU, SECUNDRBAD, CHENNAI,GUWATHATI, INDORE, JAIPUR sites
3. In We can june, August, januaury and december launch new products in this months as the number of customer will be more
4. We should focus more on months where there are less sales and try to find the probable cause as it is clearly seasonal effect
5. We can promote product id with high sales in  south and east or in DEHRADHUN, KOCHI, PATNA, RAIPUR, RANCHI, BHUBANESWAR, VIJAYAWADA, JAMMU, SECUNDRBAD, CHENNAI,GUWATHATI, INDORE, JAIPUR warehouses
6. We can promote product category (6 and 7) with high sales in  south and east or in DEHRADHUN, KOCHI, PATNA, RAIPUR, RANCHI, BHUBANESWAR, VIJAYAWADA, JAMMU, SECUNDRBAD, CHENNAI,GUWATHATI, INDORE, JAIPUR warehouses
7. We can focus on product id, product category, product size where there is less sales, find the cause and analyze further

## Hypothesis
Our null hypothesis is true i.e low MRP has comparatively high sales than high MRP has low sale

## Video of Analysis of cosmetic product (Click on the Image)

[<img src="https://img.youtube.com/vi/6_YotRYSt9g/maxresdefault.jpg" width="50%">](https://youtu.be/6_YotRYSt9g )
