## EDA results

### Future Attributes 

### Transactions 
- Days of the week (bool)

### Oil 
- Oil Price (float)

### Stores
- Store type (a-e -> 0-4, int)
- Store Cluster
- City and state they are located in (bool, onehot)

### Holidays
- Was there a holiday on this day/holiday (bool, onehot)

### Additional Notes
- remove data about April 2016 (earthquake)
- calculate stores that do not sell certain product families separately
- divide all data into 33 dataframes for each product family