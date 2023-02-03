# Real_Estate_Regression
## Predicting the selling price of a residential property using regression analysis.
Predicting the selling price of a residential property depends on a number of factors, including the property age, availability of local amenities, and location.

A dataset containing real estate sales transactions was used to predict the price-per-unit of a property based on its features. The price-per-unit in this data is based on a unit measurement of 3.3 square meters.

## The Dataset
The data consists of the following variables:

- **transaction_date** - the transaction date (for example, 2013.250=2013 March, 2013.500=2013 June, etc.)
- **house_age** - the house age (in years)
- **transit_distance** - the distance to the nearest light rail station (in meters)
- **local_convenience_stores** - the number of convenience stores within walking distance
- **latitude** - the geographic coordinate, latitude (unit: degree)
- **longitude** - the geographic coordinate, longitude (unit: degree)
- **price_per_unit** - house price of unit area (3.3 square meters)

## Task
1. Explore and prepare dataset for analysis
2. Identify and select predictive features that will help predict the price_per_unit label
3. Build a regression model that achieves the lowest Root Mean Square Error (RMSE), which must be less than 7 when evaluated against a test subset of data, will be trained and evaluated with the training subset data.

## Packages
1. Pandas
2. Matplotlib
3. seaborn
4. folium
5. sklearn
6. plotly express

## Approach
1. Data Exploration
2. Map view for estate locations using folium
3. Remove outlier values in price_per_unit
4. Correlation check
5. Separate labels and features
6. Build regression model
7. Evaluate and validate models
8. Test

>Citation: The data used in this exercise originates from the following study:

>Yeh, I. C., & Hsu, T. K. (2018). Building real estate valuation models with comparative approach through case-based reasoning. Applied Soft Computing, 65, 260-271.

>It was obtained from the UCI dataset repository (Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science).
