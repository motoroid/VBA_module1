# **VBA_module Module 2 Challenge**

## Overview of Project
The purpose of this project was to refactor code to make it more efficient.  By coding the macro to loop through 1 time it uses less steps and memory which should result in a faster run time.  This challenge also added the functionality of specifying which Workbook to analyze.  

## Results
### Original code
  ![Screenshot 2018 run time](https://user-images.githubusercontent.com/115171651/201999642-394e97f4-1acb-4755-856d-e2391a2421fa.png)
### Refactored code
![Screenshot_2018_refactored2](https://user-images.githubusercontent.com/115171651/201999698-480ffa02-31e5-4f35-ac62-0b3b9558de30.png)
## Analysis
### **Original nested loop**
![Original_loops](https://user-images.githubusercontent.com/115171651/202001002-f078d44a-ff22-47fa-8c49-7e05d8c044e5.png)
### **Refactored**
![refactored](https://user-images.githubusercontent.com/115171651/202001104-4b42d9b5-5cc5-4ef4-b84f-e46cc206d2d3.png)
## Summary
### pros vs cons old code
The original code utilized a nested loop within a loop, which results in memory having to be allocated to hold the loop within prior to running the other loop.  I think this code is a little more difficult to keep track of the i and j loops because you have to think how one nests within the other.    
### pros vs cons new code
In the new code there defined which means the code only loops through once.  Also by using the (tickerIndex) it helps keep the code more organized.  
## Reference
The first time I attempted this I only got a marginal improvement.  The copy of that code is below to show I did the work.  It wasn't until I looking through the scoring ruberik and talking with Mitch Neuenschwander from class that I was able to get a code that works well.  So the code I submitted above is very similar to his.  
![image](https://user-images.githubusercontent.com/115171651/202062499-d4dc0309-e124-403d-a1e2-fbc4329bf0cf.png)
