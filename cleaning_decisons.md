# Cleaning Decisons

The dataset was provided cleanly from the assignment so the decisions in this assignment revolved mostly around deciding which columns were most relevent to the monthly cost to a customer.

## Rows Dropped

No rows were dropped, however, there were 11 rows in `TotalCharges` without a number provided. These were likely due to new customers who had not recieved any charges at the time the data was collected. The decision was made to keep these rows due to the fact that `TotalCharges` would not be used in the training of our model. All other rows were clean.

## Columns Dropped

Only columns that were relevant to the services purchased were passed into the features DataFrame, and only the monthly charges (changed to `target`) were kept in the target DataFrame. Demographic columns, such as those indicating the customer's gender or whether they were a senior citizen were excluded from the features.