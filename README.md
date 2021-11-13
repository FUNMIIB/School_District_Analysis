# School_District_Analysis
## Overview of Project
**Background**
The school district analysis is to find the evidence that the reading and math grades for Thomas High School ninth graders has changed. The school board needs to know the extend of this dishonesty so they want to reveal any evidence.  They want Maria to exclude the freshman reading and math scores by replacing them with NaNs entries and proceed re-analyze the data by repeating the school district analysis. This project is to repeat the school district analysis to examine how replacing math and reading scores with **NaNs** affected the overall analysis in an effort to help Maria reveal any **evidence of academic dishonesty** in reading and math grades for Thomas High school ninth graders.

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

**How is the school summary affected?**
There is a slight downward change in averages and Overall passing for Thomas High School after taking 9th graders out shrunk by less than 1%. This slight decrease in averages affect other summaries.

**How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?**
Replacing the ninth graders' math and reading scores does not affect their Percent Overall Passing Mark. After replacing the ninth graders' math and reading scores, they are still within the 90 percentile passing mark.

- How does replacing the ninth-grade scores affect the 
**Math and reading scores by grade**
Calculation of average scores was not significantly affected by removing the 9th grade scores. The count() function did not include the 9th grade scores because we equate it to NaN. Thomas High School was 1174 after re-analysis, which was lesser than in the initial analysis. Percent passing score is reduced following the re-analysis but the total number of student is the same. The total passing value is reduced when I removed 9th grade scores and replaced them with NaN.

**Scores by school spending**
    The numbers are nearly the same since 9th graders are removed from the analysis. Thomas High School is in the spending bin of "630-644". When I removed the 9th grade scores, the "Percent Passing Math", "Percent Reading", and "Percent Overall Passing" scores for spending bin $630-644 are reduced after removing 9th graders.

**Scores by school size**
    Thomas HS is in the "Medium (1000-2000)" size bin. Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket "Medium (1000-2000)" 

**Scores by school type**
Thomas HS is in the "CHARTER" type bin. Removing 9th grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for type bin "CHARTER". 

**Summary**
There are changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs as reflected in average Math and Reading scores, Percent Passing Math and Reading, Overall Passing and the funding for each student. 





