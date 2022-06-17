# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
	
  The overall goal of this project was to organize and analyze data for a fundraising campaign for Louise’s play Fever.  After going through the data given, I was able to pull specific data sets to evaluate how successful other campaigns were based on their goals and launch dates.    

## Analysis and Challenges
	
  The first analysis  I did was looking at the different outcomes based on the launch dates.  I first used the YEAR function to pull the year from the “Date Created” column.  I then created a pivot table from the KickStarter sheet which I filtered by the year and “theater” category.  The pivot table shows the number of successful, failed and canceled theaters based on each month of the year.  From this table, I created a line chart to visualize the data.
  ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100322333/174204167-0d620b17-887c-4b3f-a1e1-25f1c56f9895.png)
	The second analysis I completed was determining what percent of plays succeeded, failed and were canceled based on their goal.  I created a data sheet with different goal ranges in one column and by using the COUNTIFS function, I was able to pull the number of successful, failed and canceled plays from the main Kickstarter spread sheet.  I added the numbers for each project with the associated goal range by using the SUM function and then was able to use those numbers to calculate the percentages.  To visualize the data, I created a line graph that compared the percentage of failed, successful and canceled plays to their goal ranges.
  ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100322333/174204230-83eb7196-1ac8-495a-869b-60eb07179e63.png)
	The biggest challenge I encountered while working on this project was changing the x-axis and y-axis on my second graph.  I first tried using the “select data” option on the graph to change the ranges on each axis which only resulted in error messages.  To overcome this challenge, I created a separate “area of excel chart” that just had the goal range column and the percentages columns.  I used that data set to create the appropriate graph. 

## Results

**What are two conclusions you can draw about the Outcomes based on Launch Date?**	
	After analyzing the outcomes based on goals data, I was able to conclude that across the twelve-month time period, the greatest number of successful outcomes occurred during the months of May and June.  I calculated the percentages for May and June of which came out to be 67% and 65%.
	The second conclusion I drew from the data set was the variation of percentages of canceled outcomes were very small, with a maximum percentage of seven and a minimum of zero.

**What can you conclude about the Outcomes based on Goals?**
	The first conclusion I drew after analyzing the data was that the ranges with the greatest number of percentages of success occurred within two ranges of the goal.  The goal range of 1,000 to 4,999 had the highest percent of success.  The goal range of 35,000 to 40,000 had the second highest percent of success.
	The second conclusion that I drew from this data set that the two ranges with the highest percentages of failure were 45,000 to 49,000 and 25,000 to 29,000.  The range with the highest percentage of failure was 45,000 to 49,000

**What are some limitations of this dataset?**
	I found a couple of limitations with this dataset.  One of them being that the data is limited to only three years of data.  The other limitation I discovered was the fact that it is based on country and cannot be filtered by cities within those countries.

**What are some other possible tables and/or graphs that we could create?**
	I could filter the pivot table I made for the outcomes by launch date to analyze different parent categories like film and video which I can use to create a line graph to visualize the associated numbers.  I could also take it a step further and compare those graphs with the theater graph.
	The outcomes based on goal only looked at the “plays” category.  I could run the same calculations for a different theatre subcategory like “musicals” or I could use a completely different parent category.

