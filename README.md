# Data Analyst Project 

## About Dataset

- **Source:** Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.
- **Data Set Information:** This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
- **Link:** [Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Download link:** <https://archive.ics.uci.edu/ml/machine-learning-databases/00502/online_retail_II.xlsx>

### Variables Table:

| Variable Name | Role      | Type       | Description                                                                                  | Units    | Missing Values |
|---------------|-----------|------------|----------------------------------------------------------------------------------------------|----------|----------------|
| InvoiceNo     | ID        | Categorical| a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation |          | no             |
| StockCode     | ID        | Categorical| a 5-digit integral number uniquely assigned to each distinct product                         |          | no             |
| Description   | Feature   | Categorical| product name                                                                                  |          | no             |
| Quantity      | Feature   | Integer     | the quantities of each product (item) per transaction                                         |          | no             |
| InvoiceDate   | Feature   | Date       | the day and time when each transaction was generated                                          |          | no             |
| UnitPrice     | Feature   | Continuous | product price per unit                                                                       | sterling | no             |
| CustomerID    | Feature   | Categorical| a 5-digit integral number uniquely assigned to each customer                                  |          | no             |
| Country       | Feature   | Categorical| the name of the country where each customer resides                                           |          | no             |



## Customer segmentation

Construction of customer segmentation with a focus on value pyramid: Recency, Frequency and Value

## Data Environment

```bash
conda create -n customer_segmentation
conda activate customer_segmentation
conda install pandas ipykernel matplotlib seaborn scipy scikit-learn openpyxl
```

## References

