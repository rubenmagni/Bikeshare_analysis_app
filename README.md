### Date created
This project was created on May 2, 2019\.

### Project Title
**Bikeshare Database Exploration**

### Description
This project aims to create a user\-friendly tool to quickly investigate a bikeshare database for three main US cities: Chicago, New York City, Washington DC\. This tool provides an interactive experience \- the user can filter data by day and month and obtain information including type of user, frequent routes, length of the trip, etc.

### Files used
The script is included in the file:
* bikeshare.py

The dataset is included the following files:
* chicago.csv
* new_york_city.csv
* washington.csv

### Credits
1. Convert argument to datetime:
[pandas.to_datetime](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html)
2. Convert month to number (e\.g\. January=1): [pandas.Series.dt.month](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.dt.month.html)
3. Convert day of week to a number (e\.g\. Monday=0): [pandas.DatetimeIndex.dayofweek](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DatetimeIndex.dayofweek.html)
4. Dataset was provided by [Motivate](https://www.motivateco.com/) and made available by [Udacity](https://www.udacity.com/) as part of the [Programming for Data Science Nanodegree](https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104)
