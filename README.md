# **School_District_Analysis**
## Overview of the Project
In this project, we used Pandas to analysis on a set of schools and their performances. Since there shows an evidence of academic dishonesty, we eliminated some unsure data in this analysis which are the reading and math scores for the grade nine at Thomas High School. By doing this, the data we generate will be more reliable.

## Analysis Results
### How is district summary affected?
-No effects on the number of schools, students and total budgets.
<br />-Average math scores, average reading scores, percentage passing math and reading and the overall percentage passing have decreased.
### How is school summary affected?
-The data of other schools are not affected. 
<br />-Only data of Thomas High School is affected.
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
-Since the ninth grade scores are replaced with NaN at Thomas High School, the overall grade performance is lower. As a result, when sorting schools based on scores from highest to lowest, Thomas will be moved backwards, and some others schools will be moved to forward places.
### How does replacing the ninth-grade scores affect the following:
-Math and reading scores by grade: only ninth grade will be affected since the average of math and reading scores of ninth grade at Thomas High School is lower.
<br />-Scores by school spending: the data for schools spending at $630-644 per student is affected
<br />-Scores by school size: since Thomas High School is in medium size bin, only data in this bin is affected
<br />-Socres by school type: since Thos High School is a charter school, only the data of the charter school category is affected.

## Summary of changes
-When sorting the top five schools based on % overall passing, Thomas High School is replaced with Wright High School.
<br />-When running isnull() function on student_data_df, "TRUE" appears on all ninth grade at Thomas High School.
<br />-The counts of reading_score and math_score became 38709 while total student counts is 39170.
<br />-The % passing of math and reading at Thomas High School substantially decreased.
