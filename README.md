# Overview of Project #
The purpose of this Project is to visualize the campaign outcomes based on their launch dates and their funding goals. The data set ranges from 2009 to 2017, with multiple Theatres/Plays under consideration. 


## Analysis And Challenges ##
In order to analyze the data, we created two charts:
1. A Line Chart for visualizing Theater Outcomes by Launch Date
2. A Line Chart for visualizing Outcomes Based on Goals

In order to calculate the Mean, Median and Standard Deviation we also created filtered data sets since we could not operate on the original data set. 
<br><br>

###### Analysis of Outcomes Based on Launch Date ######
After analyzing the outcomes, we were able to  conclude the following:
1. The Theater Plays are most successful between April to Aug each year, with the highest being in May.
2. There is a steady decline of Successful plays starting from October and ending on Dec each year. October also happens to be the highest number of failures every year.
3. There were no plays cancelled in October every year
<br>

![Theater Outcomes](/resources/Theater_Outcomes_vs_Launch.png)
<br><br>

###### Analysis of Outcomes Based on Goals ######
After analyzing hte outcomes, we were able to conclude the following: 
1. There were no cancelled plays in any year from 2009 to 2017
2. Since there are no cancelled plays, the successful percentage is inversely proportional to the failed percentage of Plays
3. Plays that had a range of less than $1,000 had the highest success factor
4. Plays that had a range between $35,000 to $44,999 had the second highest success factor
5. Plays that had a rnage between $45,000 to $49,999 had the highest failure rate
<br>

![Goal Outcomes](/resources/Outcomes_vs_Goals.png)
<br><br>

###### Further Analysis ######
After further investigation, we could also conclude that:
1. The mean is much higher then mode, the data is right skewed
2. The Standard Deviation is quite large from the Mean
3. It seems that there are 4 high valued plays, that have a high impact on the outcome of the anlysis
<br>

![Further Analysis](/resources/Central%20Tendency.png)
<br><br>

## Challenges and Difficulties Encountered ##
The Data Set seems to have a lot of Outliers:
1. For Successful Plays: Pledged had 58, while Goals had 73
2. For Failed Plays: Pledged had 38, while Goals had 32
<br>

![Further Analysis](/resources/Succesful%20Plays.png)
![Further Analysis](/resources/Failed%20Plays.png)
<br><br>

## Results ##
###### Theater Outcomes ######
It appears that overall the Theatres had the best rate of success from Apr to Sep on average each year. They also had the highest Failed Rate in Dec (starting from Nov to Dec) on average each year. 

###### Goal Outcomes ######
The Goal Range for "Less than 1,000" and "35,000 to 44,999" had the best outcome on average. And the worst average was from "45,000 to 49,999" range.

###### Closing Remarks ######
Further analysis could be conducted would also provide us with valuble insight:
1. Having a Stacked Chart with the "Goal Amount Ranges" and "Theater Outcomes by Launch Date" could help us in understanding any correlations. 
2. The "Outome based on Goals" is only considering data from Plays. There are a lot of other sub categories which could be considered as well. 
3. We are comparing "Theater Outcomes by Launch Date" which is considering all the Theathers, while we are only considering Plays for "Outocmes Based on Goals". There could be a correletaion if we break down and create charts from different sub categroies.
4. There are also some really high performing/value plays which are also skewing the data


