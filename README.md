# Overview of Project #
The purpose of this Project is to refactorize the code compare the performance. The goal is to also analyze the effects of refactorization, and to minimize code execution time. 


## Analysis And Challenges ##
We analyzed by modifying the code and running it against different number of tickers. We collected the different execution times for both Refactored and the Origianl Sheet for the different number of Tcikers.

In order to analyze the runtime, we created two tables:
1. Time Taken for Execution Table
2. Percentage Refactored Sheet is Faster

![Table1](/Resources/Table-ExecutionTimeTaken.png)

![Table2](/Resources/Table-PercentageRefactoredFaster.png)
<br><br>

###### Analysis Based on Refactorization of the Code ######
After plotting and anylyzing the results, we deduced that the Refactored code was much faster. 

![Table1](/Resources/Chart-RuntimeComparison.png)

<br>

![Theater Outcomes](/resources/Theater_Outcomes_vs_Launch.png)
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


