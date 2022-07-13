# Business Understanding

- Company X mainly sells products which are gifts for special occasions. Most of the company's customers are wholesale customers.

- Company X wishes to sell more products as well as introduce their products to the right customers, take care and satisfy customers.

**Objectives/Problems:** Build a system of customer segmentation based on the information provided by the company, which can help the company identify different customer groups, so they can make decisions for business strategies and customer care  appropriately.


# About Dataset

This dataset includes 541,909 rows and 8 feature variables. Each row corresponds to a customer review, and includes the variables:

**InvoiceNo:** Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

**StockCode:** Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

**Description:** Product (item) name. Nominal.

**Quantity:** The quantities of each product (item) per transaction. Numeric.

**InvoiceDate:** Invice Date and time. Numeric, the day and time when each transaction was generated.

**UnitPrice:** Unit price. Numeric, Product price per unit in sterling.

**CustomerID:** Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

**Country:** Country name. Nominal, the name of the country where each customer resides.

# About the Project

In this project, the models used were RFM, KMeans, GMM and Hierachical Clustering.
