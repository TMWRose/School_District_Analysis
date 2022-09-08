# School_District_Analysis

## Overview
In this module we helped Maria, a City Schools data analyst, analyze the data from student funding and standardized test scores. We mapped out trends and each school's performance to help the school board and superintendent makes decisions for the coming year's budget and priority lists. 
## Results

### After completing the challenge and beginning to write the ReadMe, I came to realize there was an issue with the order of the instructions that would make answering the following questions very difficult. The questions for Deliverable 3 mostly pertain to the math and reading scores, and how they are affected by removing Thomas High School 9th graders. However, upon reviewing the school summaries from the beginning of the code and after the code, I realized that the average scores hadn't changed between the summaries, only the passing percantages. I thought at first that I followed the instructions wrong, but when I went back into the data I discovered that while we did remove THS 9th grade math a reading scores, this removal came before the initial school summary was made. This means that the inital school summary _already had the THS 9th graders score data removed from it_. The percentages, however, were not altered. This is why in the second school summary at the end of the challenge the scores for THS are the exact same _but the percentages are different_ from editing them during the challenge instructions. 

1. __How is the district summary affected?__

As per the instructions given for the challenge, the district summary dataframe was only created and arranged once in the beginning of the code. Consequntly, there is no way to compare before and after removing Thomas High School's (THS) 9th graders from the dataframe. 
![district summary before edit](https://user-images.githubusercontent.com/100237685/189189077-b5119dbb-055d-498b-834c-f99a2447b177.png)


2. __How is the school summary affected?__

This is the school summary _before_ THS 9th graders were removed from the percentage KPIs
![per school summary before](https://user-images.githubusercontent.com/100237685/189205645-b8c0bc06-b2e3-4fb4-8856-780debec595f.png)
And this is _after_
![per school summary after](https://user-images.githubusercontent.com/100237685/189205656-e9560943-252e-4d7c-a1f4-e18466cc20ca.png)

The only cloumns that were changed were those pertaining to percentages. As a result of removing the 9th graders, the school's percentage passing scores went up signifigantly. 


3. __How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?__

As per the instructions given in the module, only the _percentages_ were changed 

7. __How does replacing the ninth-grade scores affect the following:__
    * ___Math and reading scores by grade___
    * ___Scores by school spending___
    * ___Scores by school size___
    * ___Scores by school type___

## Summary
