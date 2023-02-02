# Online-Retail-Customer-Segmentation
Online Retail Customer Segmentation
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
# <b>Description</b>
This is an unsupervised machine learning capstone project on customer segmentation, given by [Alma Better](https://www.almabetter.com/).
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
# <b>Problem statement</b>
In this project, Our main task is to identify major customer segments on a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail company.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. 
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
# Business Objective
The business objective for this project is to identify the major customer segments of a UK-based online retail company that sells unique all-occasion gifts using transaction data from 01/12/2010 to 09/12/2011. The company aims to understand its customer base and identify key segments to target for future sales and marketing efforts.
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
# <b>Data description (Columns involved):</b>

* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
# Recency-Frequency-Monetary (RFM) model to determine customer value:
The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase?
Frequency – How often do they purchase?
Monetary Value – How much do they spend?
A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
# Model implementation:
   * K Means.
   * K Means with elbow method.
   * Hierarchical clustering (Agglomerative).
  
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)
* Missing and duplicate values were found in the given dataset.

* Most of the purchases are from United Kingdom followed by Germany, France, Ireland and Spain.

* Most of the customers purchased items on Thursday, Wednesday, Tuesday.

* Most of the customers purchased items in the month of November, October, December, and the least number of purchases in April, January, February.

* Most of the customers start their purchase from 10:00 A.M till 2:00 P.M & the 12th hour of the day is the peak for purchasing. After 2:00 P.M the purchasing frequency gradually reduces.

* Top Five purchased products on the basis of their frequency:

   * WHITE HANGING HEART T-LIGHT HOLDER
   * REGENCY CAKESTAND 3 TIER
   * JUMBO BAG RED RETROSPOT
   * ASSORTED COLOUR BIRD ORNAMENT
   * PARTY BUNTING


• K-Means Clustering elbow method with Silhouette gives the highest score of 0.564465 for number of clusters 3.

• Sales has been increased from 2010 to 2011.

