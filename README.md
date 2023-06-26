# product-analysis-demo
Product Analysis Demo using a Kaggle dataset
This demo analysis seeks to identify trends and insights of product sales.

REC corp LTD. is small-scaled business venture established in India. 
They have been selling FOUR PRODUCTS for OVER TEN YEARS.

The products are P1, P2, P3 and P4.
They have collected data from their retail centers and organized it into a small csv file:

Q1- Total unit sales of product 1
Q2- Total unit sales of product 2
Q3- Total unit sales of product 3
Q4- Total unit sales of product 4

S1- Total revenue from product 1
S2- Total revenue from product 2
S3- Total revenue from product 3
S4- Total revenue from product 4

#### Some questions we ask:
1. What are the general trends of unit sales and revenue by year / by product?
2. What are the product sales trends by time of year / month?

### Workflow
1. Basic Setup, Data Clean
2. EDA
3. Observations
4. Applications and further analysis
   
### Basic Setup - importing library and dataset
1. import library and dataset
2. verify data set integrity
3. drop irrelevant col
4. convert obj.date to operable num
5. prep for EDA
   
![dataset](https://github.com/eunjais/product-analysis-demo/assets/107447038/a3f6c1b8-e2a8-45a4-a4aa-4341e792f5a4)

### EDA

1. Create a function for making bar chart for all four products + make bar charts
2. Total and Mean revenue of sales for each product

#### Total Unit Sales by Year
![total unit sales](https://github.com/eunjais/product-analysis-demo/assets/107447038/53e52700-88b5-48c0-8110-c0f3c9b66968)

#### Total Revenue by Year
![total revenue](https://github.com/eunjais/product-analysis-demo/assets/107447038/c18f66ce-6a35-4da3-b393-095c51c8dc50)

#### Trend in Sales   of the products by month
![months](https://github.com/eunjais/product-analysis-demo/assets/107447038/babb4bdf-2bba-43d9-be7d-a069f367d9df)

### Observations
The barchart for Total Unit Sales by Year indicates that, ranking from highest sales to lowest, P1 sold the most throughout the decade with record numbers on 2014. Following P1 is P3, P2, and P4 at the lowest units sold.

However, the chart for Total Revenue by Year indiciates that the highst revenue was brought by P3, followed by P2, P1, and P4. A cursory calaculation provided insights that there were no correlations between the unit prices of products and revenue (P3 had the second lowest price per unit, respectively). This may be reflective of the product's high popularity compared to the rest of the stock. 

### Applications + Further Analysis
While this analysis project utilized an artificial set of limited product data for basic EDA, real life applications will be far more dynamic and varied. More factors to consider include but are not limited to:
- Region Sold
- Market / Vendor Sold
- Monthly, Quarterly, Yearly trends on several factors
- etc. 
Which can help bring better insight into the business's trends. These sorts of data can help the team focus on a variety of different future goals, from marketability approaches for products that need a little more push- to predicting product sales and thus, the optimization of stock availability, which is crucial when working with live and perishable products.
Further analytic steps would veer into utilizing machine learning for accurate predictions. 

Similarly, P1 and P2 brought in similar revenues for each year. P1, despite being the most sold per unit, brought in the second lowest revenue per year, calling for potential reconsideration of its pricing.
