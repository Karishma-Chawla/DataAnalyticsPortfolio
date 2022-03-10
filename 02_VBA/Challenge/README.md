# Stock Analysis
## Overview of Project
### Background 
This project is about Steve using VBA to analyse data on stocks with an objective of advising his parents about investing in particular identified stocks. A code “All Stock Analysis” has been written to analyse information on 12 specific stock. The analysis includes Daily traded volume and Annual returns for each stock for 2017 and 2018. Code also runs a timer to calculate the time taken to run the analysis for each year. Now, Steve wants to extend this analysis for entire stock market and therefore the code has to be refactored to make it efficient.
### Purpose
The code” All Stock Analysis” has to be refactored to be executed faster in an attempt to analyse the performance of the entire stock market.


## Analysis 

### Flow of the code:
In order to compare performance, it is important to understand the workflow of the code:
1.	First step is to take the input for “Year” from the user
 ![image](https://user-images.githubusercontent.com/98617082/157594937-2af4b0de-742e-406c-9496-1b066d1f51f8.png)

2.	Next the code activates the right worksheet based on the input.
3.	Variables and arrays are defined and initialized. Variables ‘tickerindex’ and ‘tickerVolumes’ are initialized at ‘zero’.
Rows are counted to be looped over.  
![image](https://user-images.githubusercontent.com/98617082/157594984-c6ea3c01-c3b5-4439-9510-3036ffddfa0a.png)


4.	Code starts to loop over each row storing information on volume, starting price and ending price using and Conditional statement for each ticker utilizing ‘tickerindex’ to move to the next ticker.
 ![image](https://user-images.githubusercontent.com/98617082/157595003-554dfd63-4003-40cb-bbcc-e419fde9f9f8.png)

 
5.	“All stock analysis” is activate and Output is stored along with message box on the time.
![image](https://user-images.githubusercontent.com/98617082/157595018-0879a8bb-6412-4930-9401-477cc8da726b.png)
 
6.	Formatting is applied.

### Comparison of stocks for 2017 and 2018 

1.	The analysis is in for of a table that sums of Total Daily volume and Return for each of 12 stocks in the list. 
2.	The first notable comparison is that most stocks in 2017 gave a positive return and majority of the stocks gave a negative return in 2018.
3.	ENHP and RUN are outperformers in 2018 and have delivered handsome 81.9% and 84% returns.
4.	DQ and ENPH saw doubling of trading volumes in 2018 v/s 2017.

![image](https://user-images.githubusercontent.com/98617082/157595083-328628de-9060-4ff4-a09c-7250df186832.png)
![image](https://user-images.githubusercontent.com/98617082/157595095-cd8ad39a-8b5f-47e3-8481-28cc348298c0.png)


### Execution timelines of Refactored code
Execution timeline by using the refactored code is almost 1/5th of the original code from ~0.93 seconds to ~0.17seconds.
![image](https://user-images.githubusercontent.com/98617082/157595476-3e261121-408a-4160-8f40-2e18722c83f8.png)
![image](https://user-images.githubusercontent.com/98617082/157595485-00372c36-1df6-4e13-9487-f5f91316e10a.png)
![image](https://user-images.githubusercontent.com/98617082/157595500-01de1cee-5c11-4372-bf13-b5ea13a7e8ae.png)
![image](https://user-images.githubusercontent.com/98617082/157595507-2b723d82-bf21-41b2-9662-2cadfd234d1f.png)

## Summary
### Advantages of Refactoring code
1.	Time efficient: Refactoring can result in faster execution of the code thereby saving time for large data sets.
2.	Maintainability: Cleaner codes makes it easier to update and improve for long term maintenance.
3.	Scalability: Easier for programmers to alter the code to make it scalable.
4.	Easier and faster for new/existing developers to comprehend the code and make the necessary alterations.
5.	Lesser errors: Code refactoring reduces the likelihood of errors in the future and simplifies the implementation
6.	Saved money and time in future. With lower errors and easier modification, refactored can be quickly modified or debugged thereby saving time and money.

### Disadvantages of Refactoring code
1.	Risky when the application is big and existing code does not have proper test cases.
2.	Refactoring costs development time.
3.	Limited in scope. While refactoring can improve a piece of code, it cannot fix underlying architecture problems.

### Advantages of refactoring the original All Stock Analysis VBA script
1.	The refactoring has resulted in storing values for Volume, Staring Price and ending Price as it loops instead of loping through all rows to find information on each ticker thereby reducing the execution time of the code.
2.	Execution time of the code that was cut down by ~80%.
3.	The code is now scalable to a larger data set with few alterations. 
4.	Any additional dataset with just involve declaring new tickers. 

### Disadvantages of refactoring the original All Stock Analysis VBA script
1.	Refactoring code in this instance has resulted in code becoming bulkier with many more lines of code to introduce additional conditional statements. 
2.	Because of the increased lines, it can be more time consuming for new programmers to update the code at a later date.
