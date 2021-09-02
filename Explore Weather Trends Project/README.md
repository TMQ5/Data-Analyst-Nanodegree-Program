# Exploring Weather Trends
## Project Overview

In this project, we'll analyze local and global temperature data and compare the temperature trends where I live "Mecca" to overall global temperature trends and create a visualization and prepare a write up describing the similarities and differences between global temperature trends and temperature trends in Mecca.

## Project Instructions

To do this project, there are 4 steps need to follow:

#### First: Extract data from a database using a SQL query
Udacity provide a workspace to extract data from the temperatures database. There are three tables in the database:
- city_list - This contains a list of cities and countries in the database.
- city_data - This contains the average temperatures for each city by year (ºC).
- global_data - This contains the average global temperatures by year (ºC).
Thereafter, we download the results to a CSV and open it up in a spreadsheet program in order to analyze it (I used Excel).

#### Second: Calculate a moving average in a spreadsheet
Now that we extract data from a database, we'll calculate a moving average. Moving averages are used to smooth out data to make it easier to observe long term trends and not get lost in daily fluctuations. We Calculate it using AVERAGE() function in Excel.

#### Third: Create a line chart in a spreadsheet
We'll create a line chart that compares local city’s temperatures with the global temperatures and plot the moving average rather than the yearly averages in order to smooth out the lines.

#### Fourth: Make observations
Finally, we make at least 4 observations about the similarities and differences between the world averages and local city’s averages.

## Tools Used in the project
- **SQL**: used to extract data from the database.
- **Excel**: used to analyze and visualize the results of queries.


## Project Submission

The submission should be a PDF that includes:

- **An outline** of steps taken to prepare the data to be visualized in the chart, such as:
    - What tools did you use for each step? (Python, SQL, Excel, etc)
    - How did you calculate the moving average?
    - What were your key considerations when deciding how to visualize the trends?
- **Line chart** with local and global temperature trends
- At least **four observations** about the similarities and/or differences in the trends
