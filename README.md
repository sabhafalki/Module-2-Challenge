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
<br><br>


###### Further Analysis ######
We also analyzed the results further to determine how much faster the refactored code was, compared to the original code.

![Table1](/Resources/Chart-RefactoredSheetPerformance.png)
<br><br>

## Challenges and Difficulties Encountered ##
In order to analyze how the Number of Rows (i.e. Tickers) effectd the Execution Time, we had to modify the code and run it multiple times. We modified the code by adjusting the Number of Ticker Value. 
<br><br>

## Results ##
###### Runtime Screenshots ######
The following screenshots were taken for the execution times. 

1. Original Code Execution Screenshots

![Original1-2017](/Resources/Original-2017.png)

![Original1-2018](/Resources/Original-2018.png)

2. Refactored Code Execution Screenshots

![Original1-2018](/Resources/Refactored-2017.png)

![Original1-2018](/Resources/Refactored-2018.png)
<br><br>

###### Goal Outcomes ######
The Goal Range for "Less than 1,000" and "35,000 to 44,999" had the best outcome on average. And the worst average was from "45,000 to 49,999" range.

###### Closing Remarks ######
Further analysis could be conducted would also provide us with valuble insight:
1. Having a Stacked Chart with the "Goal Amount Ranges" and "Theater Outcomes by Launch Date" could help us in understanding any correlations. 
2. The "Outome based on Goals" is only considering data from Plays. There are a lot of other sub categories which could be considered as well. 
3. We are comparing "Theater Outcomes by Launch Date" which is considering all the Theathers, while we are only considering Plays for "Outocmes Based on Goals". There could be a correletaion if we break down and create charts from different sub categroies.
4. There are also some really high performing/value plays which are also skewing the data


