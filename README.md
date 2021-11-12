# School_District_Analysis
## Overview of Project
**Background**
This project is to repeat the school district analysis to examine how replacing math and reading scores with **NaNs** affected the overall analysis in an effort to help Maria reveal any **evidence of academic dishonesty** in reading and math grades for Thomas High school ninth graders.

### Purpose
**Goal**
To repeat analysis on students_complete.csv file in ordert to show the extent of academic dishonesty so that state-testing standards can be upheld

**Approach/Method**
To select the ninth-grade reading and math scores for Thomas High School using the Pandas **loc** method with conditional statements and comparison and logical operators. I then used the Pandas Numpy module to change the reading and math scores to NaN

**Results**
- How is the district summary affected?
The percent passing math, percent passing reading and percent overall passing are a little less than the original analysis as shown below
[District_summary_1.png](https://github.com/FUNMIIB/School_District_Analysis/blob/main/Resources/District_summary_1.png)
[District_summary_2.png](https://github.com/FUNMIIB/School_District_Analysis/blob/main/Resources/District_summary_2.png)

- How is the school summary affected?
Overall passing for Thomas High School after taking 9th graders out shrunk by less than 1%.

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
Replacing the ninth graders' math and reading scores does not affect either the reading or the math scores

- How does replacing the ninth-grade scores affect the 
- Math and reading scores by grade
    It has NaN after replacing them
- Scores by school spending
    The numbers are nearly the same since 9th graders are removed from the analysis
- Scores by school size
    Overall passing percentage didn't change
- Scores by school type
    No change

**Summary**
We removed the values that could alter size, spending and overall passing percentage. However, there is no significant change 



