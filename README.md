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

###### Summary ######
According to the Run-time Analysis, we were able to conlucde:
1) The Lower the number of Rows (i.e. Associated with Tickers), the lower the runtime for the code
2) The Graph appears to be linear in nature
3) Because of the lower runtimes, refactoring the code is benefitial

###### Advantages and Disadvantages of Refactoring Code in General ######
Refactoring in general has the following advantages:
1. Refactoring the Code takes time
2. Refactoring the Code makes the lines of code smaller (i.e. makes the code smaller)
3. Refactoring makes the code much more efficient (i.e. faster execution)
4. It is difficult to write refactored code from the start. Only after we have written a simple code, we can refactor it. 
<br>

Refactoring in general has the following disadvantages:
1. It requires time to refactor the code
2. It requires more effort to refactor the code
3. Sometimes refactoring the code makes it difficult to understand
<br>

###### Advantages and Disadvantages of Refactoring VBA Code ######



###### Closing Remarks ######
Further analysis could be conducted which could also provide us with valuble insight:
1. We could increase the number of rows, but duplicating the data to get more insight 
2. 


