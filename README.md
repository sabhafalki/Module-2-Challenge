# Overview of Project #
The purpose of this Project is to compare the performance improvements of the refactored VB SCript. The goal is to also analyze the effects of refactorization, and to minimize VB Script execution time. 


## Analysis And Challenges ##
We analyzed by modifying the VB Script and running it against different number of tickers (i.e. number of rows in dataset). We collected the different execution times for both Refactored and the Origianl Sheet for the different number of Tcikers.

In order to analyze the runtime, we created two tables:
1. Time Taken for Execution Table
2. Percentage Refactored Sheet is Faster

![Table1](/Resources/Table-ExecutionTimeTaken.png)

![Table2](/Resources/Table-PercentageRefactoredFaster.png)
<br><br>

###### Analysis Based on Refactorization of the Code ######
After plotting and anylyzing the results, we deduced that the Refactored VB Script was much faster. 

![Table1](/Resources/Chart-RuntimeComparison.png)
<br><br>


###### Further Analysis ######
We also analyzed the results further to determine how much faster the refactored VB Script was, compared to the original VB Script.

![Table1](/Resources/Chart-RefactoredSheetPerformance.png)
<br>

We also created a Line Chart for 2017 (for both Original and Refactored Code) where we created the Line Functions so that they can be used to estimate the execution time that is required for 'n' number of data rows in the dataset. 

![LineFunction](/Resources/LineFunction.png)
<br><br>

## Challenges and Difficulties Encountered ##
In order to analyze how the Number of Rows (i.e. Tickers) effectd the Execution Time, we had to modify the VB Script and run it multiple times. We modified the VB Script by adjusting the Number of Ticker Value. We also added Buttons so that we can easily select 2017 or 2018 stock years. 
<br><br>

## Results ##
###### Runtime Screenshots ######
The following screenshots were taken for the execution times. 

1. Original VB Script Execution Screenshots

![Original1-2017](/Resources/Original-2017.png)

![Original1-2018](/Resources/Original-2018.png)

2. Refactored VB Script Execution Screenshots

![Original1-2018](/Resources/Refactored-2017.png)

![Original1-2018](/Resources/Refactored-2018.png)
<br><br>

###### Refactoered VB Script Screenshot ######
The VB Script was refactored by limiting the redundant loop in the VB Script with the help of additional variabels (i.e. tickerIndex, tickerVolumes, tickerStartingPrices, tickerEndingPrices). The redundant loop would uncessarily loop thruogh the entire number of rows, even though it wasn't required (i.e. once we complete the iteration for a specific Ticker, we need not continue the loop).

![RefactoredVBCode-2018](/Resources/RefactoredVBCode.png)
<br><br>

## Summary ##
According to the Run-time Analysis, we were able to conlucde:
1) The Lower the number of Rows (i.e. Associated with Tickers), the lower the runtime of the VB Script.
2) The Graph appears to be linear in nature.
3) Because of the lower runtimes, refactoring the code is benefitial.
4) The number of rows is directly affecting the excution time.
<br><br>

###### Advantages and Disadvantages of Refactoring Code in General ######
Refactoring in general has the following advantages:
1. Refactoring the VB Script takes time.
2. Refactoring the VB Script makes the lines of code smaller (i.e. makes the code smaller).
3. Refactoring makes the VB Script much more efficient (i.e. faster execution).
4. It is difficult to write refactored code from the start. Only after we have written a simple VB Script, we can refactor it. 
<br>

Refactoring in general has the following disadvantages:
1. It requires time to refactor the VB Script.
2. It requires more effort to refactor the VB Script.
3. Sometimes refactoring the VB Script makes it difficult to understand.
<br><br>

###### Advantages and Disadvantages of the Original and Refactored VBA Script ######
Advantages:
1. THe Refactored VBA Script was much smaller than the original VBA Script.
2. The Refactored VBA Script was running much faster than the original VBA Script.
<br>

Disadvantages:
1. The Refactored VBA Script was much more difficult to write.
2. The Refactored VBA Script is much more difficult to interpret.
3. The Original Code was running much slower, because it would unncessarily loop throgh the entire dataset for each Ticker.
<br><br>

###### Closing Remarks ######
1. The VBA Script will only run if the dataset is sorted.
2. We could increase the number of rows, by duplicating the data (i.e. Dummy Data) to get much better insight.
3. The execution varies for each run, since it is dependent on the PC.
4. The first exeuction is always slower. Once the macro is in memory, it is much faster for subsequent runs.
5. The Line Functions can be used to estimate the required time for execution, for different number of rows. 
