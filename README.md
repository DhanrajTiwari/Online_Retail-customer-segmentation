# **Online_Retail-customer-segmentation**

In this project, the task is to identify major customer segments on a transnational data set that contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## **Data Description**

Attribute Information:InvoiceNo: Invoice number. Nominal, is a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.

StockCode: Product (item) code. Nominal, is a 5-digit integral number uniquely assigned to each distinct product.

Description: Product (item) name. Nominal.

Quantity: The quantities of each product (item) per transaction. Numeric.

InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.

UnitPrice: Unit price. Numeric, Product price per unit in sterling.

CustomerID: Customer number. Nominal, is a 5-digit integral number uniquely assigned to each customer.

Country: Country name. Nominal, is the name of the country where each customer resides.

## **Model Prediction**

The Dataset in which I am working is fully balanced data there are not any null values and missing values presents, So directly I went on model prediction in which at first I calculated RFM (Recency, Frequency, Monetary). 

And made prediction of the model using KMeans Clustering Algorithm.

## **Conclusion**

Predicted this model using KMeans Clustering Algorithm and also calculated RFM(Recency, Frequency, Monetary).  
