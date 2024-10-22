# Albany New York Weather Data Analysis

## Overview
This project focuses on analyzing historical weather data for Albany, New York
specifically looking at patterns in daily precipitation, snow depth, and snowfall.
The data is processed to calculate monthly averages over several years and
visualized to highlight trends, with particular attention from January and
December. The project utilizes data cleaning, processing, and visualization
techniques to present the findings.

### Repo Path and HTML 
Link to repository: https://github.com/connerdekok/New_York_Weather

Link to HTML: https://connerdekok.github.io/New_York_Weather/ 




### Step-by-Step Process-
1. Data Import and Initial Cleaning:
 The raw weather data, which includes various daily metrics such as
precipitation, wind speed, and temperature, is imported from a CSV
file.
 We then selected only the relevant columns for this analysis,
specifically those related to precipitation, snow depth, and snowfall,
to streamline the dataset and focus on key weather metrics.

2. Date Formatting and Sorting:
 The date column, which originally stored values as strings, is
converted into a proper date format. This allows for easier extraction
of month and year information later.
 The data is then sorted by date to ensure it&#39;s in chronological order,
which is critical for time-series analysis.
3. Extracting Year and Month Information:
 From the cleaned date column, new columns for the year and month
are created. This step allows for grouping the data by month and
year, which is essential for calculating monthly averages and
analyzing year-over-year trends.
4. Handling Special Data Values:
 Some values in the dataset, particularly in the precipitation and
snowfall columns, contain &quot;T&quot; (trace values), which indicate an
amount too small to measure. These values are replaced with zeros
to ensure accurate numerical analysis.

5. Data Conversion:

 The weather metrics related to precipitation, snow depth, and
snowfall are converted into numeric values (floats) to facilitate
calculations and statistical analysis. This step ensures the data can
be processed accurately during the aggregation step.

6. Saving Cleaned Data:
 After cleaning and processing the data, it is saved in two formats: as
a CSV file for easy access and as a database file (SQLite). Saving the
data in these formats ensures it can be easily shared or reused for
future analyses.
7. Grouping Data for Analysis:
 The dataset is grouped by month and year, allowing for the
calculation of average values for each weather metric (precipitation,
snow depth, and snowfall). This grouping step provides a summary
of how the weather changes from year to year for each month.

8. Focusing on January and February Data:
 The analysis then narrows in on specific months, particularly
January to December, to identify trends in these winter months over
multiple years. This approach is useful for identifying any significant
changes in weather patterns.

9. Visualization:
 The monthly averages from January to December are visualized
using bar charts. Each bar represents the average weather metric
(e.g., snowfall, precipitation) for a given year. These charts make it
easy to compare weather trends across years and spot any
anomalies or significant changes.

10. February Data Analysis:
 The same process used for January is applied to February data,
allowing for a direct comparison of these two winter months. This
visualization helps understand if certain patterns, such as snowfall
or precipitation, are consistent between months or change
drastically.

### How to view and website
  Clicking on the repository link (https://github.com/connerdekok/New_York_Weather) 
will bring you to where our charts can be viewed. There is a drop down menu where
you can select which month you'd like to view. Then you will see four different 
charts. First a bar chart showing the average precipitation for each year of the month selected,
and then a box and whisker chart also showing the average precipitation throughout the years.
Then there's a line chart that shows the daily maximum dry bulb temperature for each day for every year 
for the month selected, and lastly there is a another line chart that shows the average maximum, miniumum, 
and average dry bulb temperature for each year of the month selected. 

  The library not taught in class is a bootstraps library called Scrollspy where the website will
scroll to a part of the website which is selected using the links at the top of the page 

  
  

### Key Learnings-
 The project demonstrates how historical weather data can be cleaned,
processed, and visualized to extract meaningful insights.

 By focusing on specific months (January and February), we can clearly see
trends and variations in weather conditions year over year.
 The project highlights the importance of handling special values (like trace
amounts) to avoid inaccuracies in the analysis.
Tools Used
 Pandas: Used for data cleaning, sorting, and manipulation.
 Matplotlib: Used to create visual representations (bar charts) of the weather
data.
 SQLite: Used to store and query the processed data for further analysis.
 HTML and CSS.

### Conclusion-
  This weather data analysis project provides a clear overview of historical weather
trends for Albany, New York focusing on key metrics like precipitation, snow depth, and
snowfall. Through data cleaning, grouping by month and year, and visualization,
it becomes possible to better understand how the weather has evolved over time,
particularly in the winter months. The visualizations make it easy to identify
patterns and fluctuations, offering insights into broader weather trends.

  Rapid temperature and precipitation changes like observing trends
of more intense snowfall some years ad then reduced in others could be isolated incidents attributed 
to natural climate cylces, but also could be evidence of climate change. It's important to 
observe the data and trends over long periods of time to see if weather pattern changes are
isolated events or indicative of a long term change. The more years of data that is collected
and analyzed, the easier it will be to detect long term changes. 

### Presentation-

Link to slides: https://docs.google.com/presentation/d/1DDAOG-4cZrGRqtyNkuCCLL0oMCopsJek1dMTXNAw9wE/edit#slide=id.g2fcb12c194c_0_28

### Graphs-

Are located in the static folder inside of the repository.


### Credit and Sources- 

Dataset: https://www.kaggle.com/datasets/die9origephit/temperature-data-albany-new-york 

Outside of class library used: https://getbootstrap.com/docs/5.3/components/scrollspy/



