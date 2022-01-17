# Analysis of Green Stocks in 2017 and 2018

## Overview of the Project
  The purpose of this project was to analyze stock data for the client Steve.
  His parents were interested in investing into a green energy stock such as DQ since they met at Dairy Queen.
  However, Steve desired a more thorough analysis to help guide his parents.
  This project anaylzed stock data from 2017 and 2018 on green energy stocks.
  The analysis was then refactored to improve the time and memory needed to complete the analysis for the client.

## Results

### 2017

In 2017 we can see DQ managed to yield the largest return of the 12 stocks analyzed.
DQ also had the lowest volume.
Overall most of the stocks in 2017 had good returns.
The stock with the ticker "TERP" was the only stock that lost money in 2017. 
![VBA_Challenge_2017](https://user-images.githubusercontent.com/96553988/149702577-fe7192b8-aad7-4bba-b962-0ddd8a84043b.PNG)

### 2018

2018 had a much different turn out than the year prior.
This year many stocks yielded negative returns. 
DQ had the worst performance in 2018 with a return of -62.6%
On the other hand we can see "ENPH" and "RUN" performed extremely well, both displaying over 80% returns
![VBA_Challenge_2018](https://user-images.githubusercontent.com/96553988/149702588-4aa8ec27-c383-4270-bdc0-742aecbd6fe2.PNG)

## Summary

### Pros of Refactoring

In the original analysis the calculations were being ran at around 0.80 seconds.
After refactoring the analysis was ran at 0.1 and 0.08 seconds.
This difference may seem small but as data sets grow and larger analyses need to be performed, the refactored data set's value will be more noticable.
Refactoring code to run faster and use less memory is important when dealing with large data sets.
Additionally, refactoring allows the code to be more logical, and easier to read.

### Cons of Refactoring

One con of refactoring code is that it is time-consuming.
Unless the code was likely going to be used for much larger data sets, the value of refactoring might not have been worth it.
The noticable benefits of refactoring can only be seen by the coder in terms of small improvements of readiblity unless the data size grows significantly. 
