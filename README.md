# 
## by Odafe-Ighele Jesse


## Dataset 
### Overview
This dataset includes information about individual rides made in the Baywheels bike sharing system covering the greater San Fransisco Bay area in the First 3 months of 2022.
The dataset was obtained from https://s3.amazonaws.com/baywheels-data/index.htmlhttps://s3.amazonaws.com/baywheels-data/index.html and multiple files were joined together to obtain a single dataset which was wrangled to make it fit and clean for analysis.
### Wrangling steps
After importing the necessary packages and accessing the 3 datasets,the next step taken was joining the datasets together which was achieved by appending them with the aid of iterations, this facilitated the use of the months to categorize each ride.
New columns were created to utilize the already existing information , the new column created was the time duration which was captured in seconds,minutes and hours to give an accurate description of time . Due to some investigation it was observed that time durations like 0 and 1 second were obtained this was due to the same location on the starting place and destination which yielded in the same or almost similar starting and ending times being recorded this was taken care of appropriately by dropping such columns.
Some columns were renamed to give a more descriptive look to the dataset.

## Summary of Findings
My findings were aided by bar charts,histograms,stripplots,violinplots,a pointplot and a pie chart,my findings were as follows;

- I discovered the most popular type of ride
- I also realized there was a relationship between the months and the duration as well as the months and the amount of rides with March being by far the most productive month with more rides and lesser time durations 
- I realized no member made use of the docked bike and only a few casual rides made use of the docked bike
- Also with a duration limit of 60 seconds which signifies the short rides the members rides still took lesser time than casual rides hence hinting at better service for members.
- There was a general preference for the electric bike among both the casual rides and members.

## Key Insights for Presentation
The insights that stood out were;
- No member made use of the docked bike and there was a general preference for the electric bike 
- March was the best month among the first 3 months of 2022 for the Baywheels bike sharing system and there was a gradual increase in the number of rides across the first 3 months hinting at increasing popularity
The key insights answer the following questions;
- Which bike should be purchased if the Baywheels bike sharing system wants to expand its current capacity?
- Is the method at which services is being carried out working?

## Conclusion
The Baywheels bike sharing system dataset was a very insightful one and the insights obtained will surely help the business make well informed decisions.


