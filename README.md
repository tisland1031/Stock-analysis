# Stock-analysis
## Overview of Project
The project entailed performing data analysis for stocks in years 2017 and 2018. The original code used nesting loop statements to analyze thousands of stocks. However, to increase efficiency and decrease code run time, refactor code will be utilized.   

### Purpose
The purpose of this project was to refactor the original code in Visual Basic Application (VBA) for all stocks in both years, 2017 and 2018, and witness an increase in macro run time and efficiency while comparing the original script. Determination will be made if the refactored code was successful in achieving a faster run time.  

## Results
The original script was written using a nested loop. The code included two variables, starting and ending price.

The original code is demonstrated below:

![VBA_Challenge_Original Code](https://user-images.githubusercontent.com/96746207/155914923-878c4773-c985-40cf-99c3-bb0435cd18c0.png)

 The below information produced run times of 0.703125 seconds and 0.65625 seconds.

![VBA_Challenge_2017_Original Code](https://user-images.githubusercontent.com/96746207/155915599-cca68b1c-64aa-4484-9cfa-c38308e8d63d.png)
![VBA_Challenge_2018_Original Code](https://user-images.githubusercontent.com/96746207/155915624-8839de84-36d2-47ca-92cf-aa938cfac70a.png)


### Analysis of Refactored VBA Script
The refactored scripts used arrays and series of loops. The nesting loops were not needed. The refactored code looped through the data only one time. A ticker index was created as a variable

The refactored script created three output arrays:
-	Tickervolume 
-	tickerStartingprices 
-	tickerEndingPrice
	
The refactored code is demonstrated below:

![VBA_Challenge_Refactored Code ](https://user-images.githubusercontent.com/96746207/155914948-6818a104-7b1d-4944-983c-a6f35dd3083f.png)

The refactored code below demonstrated a faster macro run time for both years, 0.0703125 seconds. 

![VBA_Challenge_2017](https://user-images.githubusercontent.com/96746207/155912775-a5430d77-46b0-4171-8ce7-755f940fb4e9.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/96746207/156268018-6fb8d5af-d277-4e58-a537-593afa1440fb.png)



## Summary
- Refactoring code has both advantages and disadvantages. Refactoring script significantly decreased the macro run time for the data set. While working with very large data set this would be extremely helpful, efficient and organized. However, refactoring code has disadvantages. The end user needs to be aware of duplicating code and/or making changes in the wrong area of the script; If not, the refactoring script will produce many errors.   

- Experienced both advantages and disadvantages of the original and refactored VBA script. The refactored script did exhibit a faster macro run time. The code was more organized and easier to read. However, noticed different run times while running the code throughout the project but overall, the refactored code ran faster than the original code. The second issue with the refactored script was received errors when no errors were found; needed to copy and pasted the code into Visual Studio Code application. However, the refactored code produced a faster run time and was more efficient compared to the original code.       
