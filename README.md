Write a Data Science Blog Post
Udacity Data Scientist Nanodegree Project

This is the repo of the Write a Data Science Blog Post project for the Udacity Data Scientist Nanodegree Project.

1- Business Understanding

In this project, we are analyzing conflict events data in Sudan from 2021 to 2023. The goal is to gain insights into the types of conflict events, the regions most affected by the conflict, and to predict the likelihood of civilian casualties based on the conflict type, region, and time of day.


For this, we asked 4 questions:
1. What are the total fatalities caused by each conflict type? And number of fatalities in each region?
2. What are the main drivers of conflict in Sudan, according to the ACLED data? Are these drivers consistent across different regions of the country, or do they vary depending on local circumstances?
3. How has the conflict in Sudan evolved over the past two years?
4. What is the impact of the conflict in Sudan on civilians, and how has this changed over time? Are there particular groups or regions of the country that are especially vulnerable to violence?

2- Data Understanding
The data comes from the ACLED website. we downloaded sudan data from 25 october 2021 to 10 feburaury 2023.
the data contains, conflicit types, regions, event date ,describtion for event and many other details.


3- Prepare Data

We begin by importing the ACLED dataset for Sudan from 2021 to 2023 and cleaning the data. We rename some of the columns to make them more readable and convert the date_time column to a datetime format. We also filter out events with missing or incomplete data and create new columns for the year, month, and day of each event.

4- Data Modeling

we graphed different event types and fatailites that were relevant to the 4 questions, with the python libraries matplotlib and sklearn.metrics.

5- Evaluate the Results

for the 4 questions, we arrived at the following conclusions:

highest number of fatalites caused by batteles, and west darfur has higest number of fatalities.
seems that protest and other type of events contunied in the past 2 years, and khartoum state registered higest number of protests, on the other hand west darfur has higest number of battles.


the libraries used: Pandas, Matplotlib and sklearn.metrics libraries. 
the motivation for the project: As a Sudanese citizen, I am motivated to analyze the ACLED data on Sudan in order to better understand the drivers and impact of the conflict on the civilian population. 
By identifying trends and patterns in the data, I hope to gain insight into the most vulnerable regions and populations, 
as well as the effectiveness of current protection and mitigation efforts. Ultimately, 
this analysis will inform my work and that of my colleagues, helping us to better target our resources and interventions to support those most affected by the conflict.

File Description:
SudanConflicit.ipynp : Notebook containing the full process, loading, cleaning and analyzing data.
SudanConflict.py: python script containing the full process, loading, cleaning and analyzing data. 
SudanData.csv: Data file used.
Licensing, Authors, Acknowledgements
the data is downloaded from ACLED website. i achnowledge Udacity team for clear leasons and great support.
