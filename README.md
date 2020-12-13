# Seattle Airbnb Data Analysis & Modeling

## Project Motivation

I want to use Seattle Airbnb data to create price prediction model. This model could be used to help host (especially the new one) to set proper price for their listing. So, after they fill out their listing information, they will get the price recommendation (that the model output).

We do exploratory data analysis and answer these questions:
- Since the demand at weekend will be higher than weekday, the hosts will put the price higher in the weekend. Could we validate this assumption?
- Which neighbourhood area has the highest average price?
- Is there any correlation between number of listing (at neighbourhood area) and price?
- Could we create model to predict price of the listing, given: location (neighbourhood), property type, room type, number of accomodated people (accomodates), number of bathrooms, number of bedrooms, number of beds, bed type, and amenities? 

## File Description

- A Jupyter Notebook
- Dataset:
   Dataset Link: https://www.kaggle.com/airbnb/seattle/data
   The following Airbnb activity is included in this Seattle dataset:
   - Listings, including full descriptions and average review score
   - Reviews, including unique id for each reviewer and detailed comments
   - Calendar, including listing id and the price and availability for that day

## Conclusion

Results: 
- Almost 48.6% of listings has higher price on weekend, 42.9% of listings has the same price on weekend, and only 8% of listings has lower price on weekend. On average, price of the listing is increased 4.4% on weekend.
- Neighbourhood that has highest average price is Southeast Magnolia.
- Correlation between Total Listing and Average Price is quite low.
- We could create price prediction model using those features, with Mean Absolute Error around $36 (from Test Dataset). We also could recommend the host to increase price on weekend by 4-5%. However I think that MAE (Mean Absolute Error) could be improved if we add more data or more features.


