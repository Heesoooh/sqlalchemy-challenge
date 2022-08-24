# sqlalchemy-challenge

## Purpose of Project
In order to help with trip planning to Honolulu, Hawaii, I need to do some climate analysis on the area.
In this assignment, you'll complete challenge using Python, SQLAlchemy, Pandas and Matplotlib. 
### Part 1: Climate Analysis and Exploration
In this section, you’ll use Python and SQLAlchemy to perform basic climate analysis and data exploration of your climate database. Complete the following tasks by using SQLAlchemy ORM queries, Pandas, and Matplotlib.
- Use the provided starter notebook and hawaii.sqlite files to complete your climate analysis and data exploration.
- Use SQLAlchemy’s create_engine to connect to your SQLite database.
- Use SQLAlchemy’s automap_base() to reflect your tables into classes and save a reference to those classes called Station and Measurement.

Link Python to the database by creating a SQLAlchemy session.
Important: Don't forget to close out your session at the end of your notebook.

Precipitation Analysis:
To perform an analysis of precipitation in the area, do the following:
- Find the most recent date in the dataset.
- Using this date, retrieve the previous 12 months of precipitation data by querying the 12 previous months of data. Note: Do not pass in the date as a variable to your query.
- Select only the date and prcp values.
- Load the query results into a Pandas DataFrame, and set the index to the date column.
- Sort the DataFrame values by date.

Station Analysis:
- To perform an analysis of stations in the area, do the following:
- Design a query to calculate the total number of stations in the dataset.
- Design a query to find the most active stations (the stations with the most rows).
- Design a query to retrieve the previous 12 months of temperature observation data (TOBS).

### Part 2: Design Your Climate App
Now that you have completed your initial analysis, you’ll design a Flask API based on the queries that you have just developed. 
- Homepage
- Precipitation
- Stations
- tobs
- Start and End

## Analysis 

### Climate Analysis and Exploration
In this challenge we created <a href="climate_starter.ipynb">code</a> to do precipitation and stations analysis 
<img src="Images/precipitation.png" width="500">

### Climate App
In this challenge we created <a href="app.py">code</a> to design a flask API based on the data that I developed.

## Results
From analysis, in between Sep and October 2016 had most precipitation over 6inches followed by the May 2017 with just over 6 inches. From 2016-2017, maximum precipitation was 6.7 inches. 
There are total 9 stations, and from the Waihee Station Temperature Observations, most frequent temperature was 75.

## Recommandation 
From the analysis, the best time to travel Honolulu, Hawaii is April, June, July and August. 
