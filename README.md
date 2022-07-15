# School_District_Analysis
New repo for School District Analysis

## Overview of the school district analysis:
 
## The purpose of this analysis
The purpose of this analysis was to clean up the data on schools grades. There has been an evidence of dishonesty on reading and math grades for Thomas High School. Ninth graders appeared to have been altered. As a data analyst, my job was to clean the data on Thomas High School's math and reading scores. I replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. In addition, a report was created below how the changes affected the overall result of school ranking. The report also summarizes student grade performances based on their budget.

## Results:

### How is the school summary affected?
Below is a snapshot of school summary before replacing Thomas High School ninth graders from the data.
![School Summary Before Removing THS Ninth Graders](https://user-images.githubusercontent.com/106283411/179303656-8813153f-c63e-48a7-a70b-548ef2a592a0.png)




Below is a snapshot of school summary after replacing Thomas High School(THS) ningth graders from the data. The overall passing rate on Thomas High School dropped 
from 90.95% before replacing THS ninth graders to 65.08%. This is a significant drop of 28% difference.
![School Summary After Removing THS Ninth Graders](https://user-images.githubusercontent.com/106283411/179303754-4f1f55d7-b5b7-425e-9267-a95b85495d7d.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

### How does replacing the ninth-grade scores affect the following:

### * Math and reading scores by grade. 
Overall the math and reading scores were not affected except for Thomas High School since the ninth grader scores were replaced with NaNs.

Ninth Grade Math Scores
![ninth_grade_math_scores](https://user-images.githubusercontent.com/106283411/179306778-fbe60765-3615-4b73-9e1d-185444988279.png)


Ninth Grade Reading Scores
![ninth_grade_reading_scores](https://user-images.githubusercontent.com/106283411/179304095-bbf3224f-9b92-4026-ad1b-64e19c8fd87d.png)



### * Scores by school spending
The scores had no affect on per school spending. These are set numbers spend per student from each high school however the changes can be seen on Spending Ranges (Per Student) under $631-645 before and after replacement of ninth-grade at Thomals High School. The percentage changed on overall passing changed from 62.86% to 56.39% under $631-645 spending ranges. This is due to the number of students was reduced after replacing the THS ninth-graders.
![Scores by School Spending_before_ninth_grade](https://user-images.githubusercontent.com/106283411/179304154-70b39093-f87c-4d9b-8c19-9b940ff25327.png)

![Scores by School Spending_after_ninth_grade_replacement](https://user-images.githubusercontent.com/106283411/179304202-2989012d-c160-4233-ac24-e372e1c8d3c3.png)




### * Scores by school size
Under the same School Size - Medium (1000-1999), the overall passing math and reading had changed due the sum calculation used under that column after the replacement of THS ninth-graders to calculate the mean.
![Scores by School Size Before Ninth Graders](https://user-images.githubusercontent.com/106283411/179304251-2e0bd048-cbf4-4237-a17d-676d3ebf8ef5.png)

![Scores by School Size After Ninth Graders](https://user-images.githubusercontent.com/106283411/179304289-f333583b-fffd-4df3-b9e2-83382f984b92.png)




### * Scores by school type
The the top 5 high schools, there are all Chaartered school which included Thomas High School. After the replacement of ninth-graders at Thomas High School, Wright High School replaced Thomas High school. 

Top Five Schools are all Chartered Schools.
![Top_five_schools_before](https://user-images.githubusercontent.com/106283411/179304493-a9d9679c-14cd-4c76-8bd5-816336478caf.png)


There are no changes on the buttom 5 high schools by type. It is all District Schools. 
Top Below Schools are all District Schools
![Top_five_schools_after](https://user-images.githubusercontent.com/106283411/179304424-570b4f47-92f8-464c-a872-8d8839878624.png)




## Summary:

In summary, the replacement of ninth-grade scores affected the overall Math and reading scores by grade, by spending, size and type due to the reduced amount of students included in the calculations. 
