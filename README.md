# **VBA_module Module 2 Challenge**

## Overview of Project
The purpose of this project was to refactor code to make it more efficient.  By coding the macro to loop through 1 time it uses less steps and memory which should result in a faster run time.  This challenge also added the functionality of specifying which Workbook to analyze.  

## Results
### Original code
  ![Screenshot 2018 run time](https://user-images.githubusercontent.com/115171651/201999642-394e97f4-1acb-4755-856d-e2391a2421fa.png)
### Refactored code
![Screenshot_2018_refactored2](https://user-images.githubusercontent.com/115171651/201999698-480ffa02-31e5-4f35-ac62-0b3b9558de30.png)
## Analysis
The original code utilized a nested loop within a loop, which results in memory having to be allocated to hold the loop within prior to running the other loop.  There was also do defined end like in the refactored which has you one through it once.  
### **Original nested loop**
![Original_loops](https://user-images.githubusercontent.com/115171651/202001002-f078d44a-ff22-47fa-8c49-7e05d8c044e5.png)
### **Refactored**
![refactored](https://user-images.githubusercontent.com/115171651/202001104-4b42d9b5-5cc5-4ef4-b84f-e46cc206d2d3.png)
## Summary
### pros vs cons old code
### pros vs cons new code
