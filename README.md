Fresh Analytics, a data analytics company, aims to comprehend and predict the demand
for various items across restaurants. To accurately forecast the sales of items across
different restaurants over the years, enabling better decision-making and planning.

3 datasets are provided:
restaurants.csv: This data provides information about the restaurants or store.
items.csv: This data contains information about items.
sales.csv: This contains the count of a particular item sold at a particular store
or restaurant for different dates.

Task
------
a. Import the datasets into the Python environment.
b. Examine the dataset's shape and structure, and look out for any outlier
c. Merge the datasets into a single dataset that includes the date, item id, price, item count, item
names, kcal values, store id, and store name
Exploratory data analysis:
a. b. c. d. Examine the overall sales to understand the pattern
Find out how sales fluctuate across different days of the week
Look for any noticeable trends in the sales data for different months of the year
Examine the sales distribution across different quarters averaged over the years. Identify any
noticeable patterns.
e. Compare the performances of the different restaurants. Find out which restaurant had the most
sales and look at the sales for each restaurant across different years, months, and days.
f. Identify the most popular items overall and the stores where they are being sold. Also, find
out the most popular item at each store
g. Determine if the store with the highest sales volume is also making the most money per day
h. Identify the most expensive item at each restaurant and find out its calorie count

Forecasting using machine learning algorithms:
a. Build and compare linear regression, random forest, and XGBoost models for predictions
• Generate necessary features for the development of these models, like day of the week,
quarter of the year, month, year, day of the month and so on
• Use the data from the last six months as the testing data
• Compute the root mean square error (RMSE) values for each model to compare their
performances
• Use the best-performing models to make a forecast for the next year


