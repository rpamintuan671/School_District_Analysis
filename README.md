# School_District_Analysis
New repo for School District Analysis

## Overview of the school district analysis:
 
## The purpose of this analysis
The purpose of this analysis was to clean up the data on schools grades. There has been an evidence of dishonesty on reading and math grades for Thomas High School. Ninth graders appeared to have been altered. As a data analyst, my job was to clean the data on Thomas High School's math and reading scores. I replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. In addition, a report was created below how the changes affected the overall result of school ranking. The report also summarizes student grade performances based on their budget.

## Results:
Markup : * Bullet list
### * How is the school summary affected?
Below is a snapshot of school summary before replacing Thomas High School ninth graders from the data.


Below is a snapshot of school summary after replacing Thomas High School(THS) ningth graders from the data. The overall passing rate on Thomas High School dropped from 90.95% before replacing THS ninth graders to 65.08%. This is a significant drop of 28% difference.


### * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

### * How does replacing the ninth-grade scores affect the following:
        - Math and reading scores by grade. 
            Overall the math and reading scores were not affected except for Thomas High School since the ninth grader scores were replaced with NaNs.

        - Scores by school spending
            The scores had no affect on per school spending. These are set numbers spend per student from each high school however the changes can be seen on Spending Ranges (Per Student) under $631-645 before and after replacement of ninth-grade at Thomals High School. The percentage changed on overall passing changed from 62.86% to 56.39% under $631-645 spending ranges. This is due to the number of students was reduced after replacing the THS ninth-graders.


        - Scores by school size
            Under the same School Size - Medium (1000-1999), the overall passing math and reading had changed due the sum calculation used under that column after the replacement of THS ninth-graders to calculate the mean.



        - Scores by school type
            The the top 5 high schools, there are all Chaartered school which included Thomas High School. After the replacement of ninth-graders at Thomas High School, Wright High School replaced Thomas High school. 


            There are no changes on the buttom 5 high schools by type. It is all District Schools. 




## Summary:

In summary, the replacement of ninth-grade scores affected the overall Math and reading scores by grade, by spending, size and type due to the reduced amount of students included in the calculations. 