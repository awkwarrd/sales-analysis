## Sales Forecasting Time Series Dataset Brainstorm

### Hypotheses and ideas

### Transactions.csv

- Checking sales by day of the week
- Checking sales by day of the month (since salaries are paid on the 15th day of the month and on the last day).
- Check sales by month
- Checking the schedule of stores

### Oil.csv

- Interpolate oil prices and check the relationship with target/transactions

### Stores.csv

- Checking the relationship between a store's sales and
    1. its type
    2. the city in which it is located
    3. the state in which it is located
    4. its cluster

#### Holidays.csv

- Checking correlations between each individual holiday and sales levels
- Check correlations between sales levels and holidays as a whole


### Training_data.csv

- Checking the training dataset for outliers and anomalies
- Checking which product families are sold in each store

### Other

- Partitioning the dataframe into 33 for each product family and creating model for each product family