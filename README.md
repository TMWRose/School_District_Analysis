# School_District_Analysis

## Overview
In this module we helped Maria, a City Schools data analyst, analyze the data from student funding and standardized test scores. We mapped out trends and each school's performance to help the school board and superintendent makes decisions for the coming year's budget and priority lists. 
## Results

`After completing the challenge and beginning to write the ReadMe, I came to realize there was an issue with the order of the instructions that would make answering the following questions very difficult. The questions for Deliverable 3 mostly pertain to the math and reading scores and how they are affected by removing Thomas High School 9th graders. However, upon reviewing the school summaries from the beginning and end of the code, I realized that the average scores hadn't changed between the summaries, only the passing percantages. I thought at first that I followed the instructions wrong, but when I went to check I discovered that while we did remove THS 9th grade math a reading scores, this removal came BEFORE the initial school summary was made. This means that the inital school summary already had the THS 9th grader's score data removed from it. The percentages, however, were not altered. This is why in the second school summary at the end of the challenge the scores for THS are the exact same but the percentages are different. Consequently, due to the shortsight in the instructions, I will be answering the following questions as if they were asking about math, reading, and overall percentages, not the scores, as those were the the only things to have changed.  `

1. __How is the district summary affected?__

As per the instructions given for the challenge, the district summary dataframe was only created and arranged once in the beginning of the code. As a result, there is no way to compare before and after removing Thomas High School's (THS) 9th graders from the dataframe. 
![district summary before edit](https://user-images.githubusercontent.com/100237685/189189077-b5119dbb-055d-498b-834c-f99a2447b177.png)


2. __How is the school summary affected?__

This is the school summary _before_ THS 9th graders were removed from the percentage KPIs
![per school summary before](https://user-images.githubusercontent.com/100237685/189205645-b8c0bc06-b2e3-4fb4-8856-780debec595f.png)
And this is _after_
![per school summary after](https://user-images.githubusercontent.com/100237685/189205656-e9560943-252e-4d7c-a1f4-e18466cc20ca.png)

The only cloumns that were changed were those pertaining to percentages. As a result of removing the 9th graders, the school's percentage passing scores went up signifigantly. This makes it seem as those THS is doing much better in math and reading than it actually is.


3. __How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?__

(As per the instructions given in the module, only the _percentages_ were changed) Before removing the 9th graders, THS was part of the 8/15 schools that had about 66% of their students passing math and the lowest percentage of students passing reading at about 69%. After removing the 9th graders, THS's data presented as if the majority of their students were passing both subjects, putting them on par with 7/15 of the other schools. 

7. __How does replacing the ninth-grade scores affect the following:__
    * ___Math and reading scores by grade___
         * The math and reading percentages __by grade__ were not calculated in this challenge. As such, there is nothing to compare them to. Even if they were, or the code was written correctly to be able to do a before and after of removing the 9th graders, the 9th graders being removed does not affect the other grades __individual__ scores, so this question is irrelevant. The only change would be the 9th grader's scores before they were NaN'd and after. 
    * ___Scores by school spending___
         * It appears that the larger the school budget was, the lower the passing percenatges were.
         * ![budget](https://user-images.githubusercontent.com/100237685/189217441-e8b73be2-b3f5-4375-a601-4d178274e6f6.png)
  
    * ___Scores by school size___
         * Small and medium school had all passing percentages in the 90s, but large schools had their pssinf percentages in the 50s-80s. They did signifigantly worse than the other two school sizes.  
         * ![size](https://user-images.githubusercontent.com/100237685/189217469-f73cd3b2-8d53-4092-80a5-a70730e70cca.png)

    * ___Scores by school type___
         * Charter outperformed district in almost the exact same way small/medium schools outperformed larger schools
         * ![type](https://user-images.githubusercontent.com/100237685/189217497-278f4fda-9ead-408f-bf77-a591ad004df3.png)


## Summary
