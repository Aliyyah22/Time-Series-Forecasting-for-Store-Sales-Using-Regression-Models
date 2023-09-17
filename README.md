# Time-Series-Forecasting-for-Store-Sales.
## Business Objective
Accurate prediction of store sales is crucial in a business because it serves as a foundational element for multiple aspects of a business's operations.
This project involves predicting store sales using data obtained from Corporation Favorita, a prominent grocery retailer based in Ecuador. The primary objective involves developing a robust and accurate time series forecasting model that predicts store sales for a wide range of products across Favorita stores.

## Data Understanding
### train.csv
The training dataset consists of time series data that includes features like store_nbr, family, onpromotion, and the target variable, which is sales.
store_nbr(store number) identifies the store at which the products are sold.
family identifies the type of product sold.
sales gives the total sales for a product family at a particular store at a given date. 
onpromotion gives the total number of items in a product family that was being promoted at a store on a given date.

### test.csv
The test data has the same features as the training data. We will predict the target sales for the dates in this file.
The dates in the test data are for the 15 days after the last date in the training data.

### transaction.csv
It contains the date, store_nbr and transactions made on that particular date.

### sample_submission.csv
A sample submission file in the correct format.

### stores.csv
The store data includes the city, state, type, and cluster.
The cluster is a grouping of similar stores.

### oil.csv
It contains the date and the dcoilwtico. The "dcoilwtico" data represents the daily values of the West Texas Intermediate(WTI)crude oil price index, which is important for tracking and analyzing trends in the oil market. Ecuador is an oil-dependent country and its economic health is highly vulnerable to shocks in oil prices.

### holidays_events.csv
It contains the date, type, locale, locale_name, description, and the transferred column. The "transferred" column in the data indicates whether a holiday is observed on a different date than its actual or traditional date.
