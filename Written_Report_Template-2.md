# An Analysis of Kickstarter Campaigns

## Overview of Project

Play-writer is seeking technical analysis of campaign outcomes using Kickstarter crowdfunding platform. 

###Purpose
 
Re-visit to Play-writer Louise's crowdfunding campaign for U.S. plays using the Kickstarter platform. The purpose of this technical analysis was to determine if a relationship exists between types of campaigns, launch date, and funding.

##Analysis of Outcomes Based on Launch Date

Selecting the entire current dataset, a pivot table was inserted to summarize outcome statistic. There were resources available to guide the criteria selection. First, the Years() function was needed to extract the year from the complete launch date created. Tis allowed for filtering by year, and later grouping by month to narrow down the most successful timing for launches. The images provided a way to determine if the categories filled the correct field locations. The fields were filled as followed:
'Filters:  Parent , Years
'Rows: Date Created Converted (grouped by month)
'Column:  Outcomes
'Values:  Count of Outcomes
This pivot table provided a way to extract the visualization "Theater Outcomes Based on Launch Date" line chart for better client understanding.

Concerning the theater category, May had the best rate of successful and failed launch dates; and January had the highest frequency of cancelations. Additionally, a line graph created representing the correlation between goal amount and campaign outcome. Overall there was a negative correlation in the subcategory of "Plays" between successful campaign outcomes goal amount under $30,000. More than or equal to $30,000 demonstrated a positive relation ship, followed by a sharp decline from the $45,000 to $49,999 range, at which the positive trend rebounded. There were no cancelations for this subcategory to the failure outcome mirrors the success rate for at all goal points.

The pivot chart filtered all years of the related to the Theater "parent" category. Based on the monthly result, May was the most popular month to launch a campaign and provides the optimal rate for successful launches. May not only historically demonstrates the the best overall outcome, but also a relatively low cancelation rate. Because May had the biggest sample size, it also had the highest count of failed launches, though December provided the worst rate at nearly 50% failure rate. January had the highest rate of cancelations. See Line Chart below title "Theater Outcomes Based on Launch Date"

[TheaterLuanchdate]https://github.com/Quinneth/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png

##Challenges and Difficulties Encountered

Determining where to place each field name was challenging. Also, it was hard to determine how to use the grouping function to break each year into months

## Analysis of Outcomes Based on Goals

Using the function COUNTIFS(), this analysis is able to filter specific criteria, in this scenario goal range, as well as combine several categorical criteria of interest like outcomes of play. The summation function SUM(), produces the number of successful, failed, and canceled projects for each goal range. The percentage of each outcome was then calculated for easier interpretation of results. See "Outcomes Based on Goals" line chart below

[Outcomebasedongaols]

## Challenges and Difficulties Encountered

The CountIFs() function can be complex depending on the number criteria and ranges involved, next time, it may be easier to give each value its own cell to aid in the number of errors in data entry.

# Results

## What are two conclusions you can draw about the Outcomes based on Launch Date?

1 Best Month for launching theatrical crowdfunding campaign is May

2 Worst Month for launching theatrical crowdfunding campaign is December

3 Month most likely to be canceled is January, while least likely is October

## What can you conclude about the Outcomes based on Goals?

1 The most successful campaign outcomes are based on goals less than $5000, followed by $35,000-44,999.
 
2 The least successful campaign outcomes occurred in the goal range of $45,000-$49,999, followed by the $25,000-$34,000.

#What are some limitations of this dataset?

Limitations of this data set include completeness. Although the dataset is robust, it is only one a sample of crowdfunding projects in general an therefore does not include similar sites nor the entire population of projects that were crowdfunded for range of years. The dataset also does not include any externalities like macro or micro economic conditions. 

# What are some other possible tables and/or graphs that we could create?
It might be helpful have a visualization of duration of theatrical campaigns and end dates. Also, providing a pivot table chart based on the number of successful outcomes each year, may provide trend insights.
