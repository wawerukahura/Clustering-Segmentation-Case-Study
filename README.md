# Clustering-Segmentation-Case-Study

Customer segmentation is highly significant in determining what action is required to grow revenue, establish strong relationships with customers, and many other things. Customer segmentation would provide us with a reference point for taking action for each consumer in their segmentation, such as product differentiation, creating a focus campaign for each customer, and other strategies that we have. Companies would focus on a priority scale as a result of customer segmentation. This segmentation allows us to reach out to "star" customers who make large purchases as well as "rare" customers who make little purchases. Companies may concentrate their efforts, resources, and attention on that specific segment.

I will use machine learning approaches to construct correct consumer segments because we have a customer segmentation problem.

It contains 8 attributes which are fully described below:

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.

METHODOLOGY

In this instance, l processed and analyzed a dataset for a non-store internet retailer. Each step is detailed in the notebooks. This project is summarized as follows:

The first step is data cleaning and preprocessing so we can feed good and cleaned data to the next levels.

The second step is EDA and data visualization and I inspected the cleaned data for useful information. 

In the last step I used clustering for customer segmentation and to find customer groups with similar behaviors for further analysis and business strategy planning. In this section also tried to find the best association rules and to see which set of products were often bought together.

