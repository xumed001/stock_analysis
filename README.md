# Stock Analysis Overview
This analysis looks into the data from 12 tickers in stock market for the year 2017 & 2018. First half of the analysis we use VBA script to clean and organize the data. Stocks are organized by its ticker name, total volume and its return for the year. The data sheet is also formatted by color and text for better readability. Macros are assigned so that the user can easily interact with the data. For the second half we refactor the script for it to run more effeciently. This improves the script and optimizes it if the user wants to run analysis on bigger projects.

## Results 
### Original
<img src="Resources/2017_b4_refactor.png" width="400"> <img src="Resources/2018_b4_refactor.png" width="400">

The original script tries to solve the problem with nested for loop which is not always efficient and also makes the code harder to read and understand.

### refactored 
<img src="Resources/VBA_Challange_2017.png" width="400"> <img src="Resources/VBA_Challange_2018.png" width="400">

The refactored code subsitutes nested for loop by adding arrays and variable and efficently using it on one loop. Which improves the code run time and readability. 

## Summary

