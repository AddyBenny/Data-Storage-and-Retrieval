# Data-Storage-and-Retrieval
10_Advanced_Data_Storage_and_Retrieval

Step 1 - Climate Analysis and Exploration
- I used Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database. All of the following analysis were completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.

- I choose a start date and end date for your trip. The vacation range is approximately 3-15 days total.
- Used SQLAlchemy create_engine to connect to your sqlite database.
- Used SQLAlchemy automap_base() to reflect my tables into classes and saved a reference to those classes called Station and Measurement.

Precipitation Analysis
- Designed a query to retrieve the last 12 months of precipitation data.
- Selected only the date and prcp values.
- Load the query results into a Pandas DataFrame and set the index to the date column.
- Sort the DataFrame values by date.
- Plot the results using the DataFrame plot method.
- Used Pandas to print the summary statistics for the precipitation data.

Station Analysis
- Designed a query to calculate the total number of stations.
- Designed a query to find the most active stations.
- List the stations and observation counts in descending order.
- Designed a query to retrieve the last 12 months of temperature observation data (TOBS).
- Filter by the station with the highest number of observations
- Plot the results as a histogram with bins=12.



