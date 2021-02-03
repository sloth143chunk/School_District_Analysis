# School_District_Analysis

## Project Overview

The purpose of this analysis was to provide the school board with:
-	A high-level snapshot of the district's key metrics, presented in a table format
-	An overview of the key metrics for each school, presented in a table format
-	To check for evidence of academic dishonesty by one of the schools
Tables presenting each of the following metrics:
-	Top 5 and bottom 5 performing schools, based on the overall passing rate
-	The average math score received by students in each grade level at each school
-	The average reading score received by students in each grade level at each school
-	School performance based on the budget per student
-	School performance based on the school size 
-	School performance based on the type of school


## Results

-	The district summary shows no significant changes

![District Summary](/District_summary.PNG)
-	The school summary shows significant changes in the reading, math and overall passing percentages

![School Summary](/School_summary.PNG)
-	Replacing the ninth graders scores shows that Thomas High School did not have a passing percentage for reading, math, and overall compared to other schools in the district
-	With scores by grade, the 9th grade column shows “NaN”, scores compared to spending, size and type all showed drops in passing percentage

![Scores By Grade](/Scores_by_grade.PNG)
![Spending Summary](/Spending_summary.PNG)
![Size Summary](/Size_summary.PNG)
![Type Summary](/Type_summary.PNG)

## Summary

After updating the school district analysis and Thomas High School’s 9th graders with “NaN” scores, there were noticeable drops for reading, math and overall passing percentages.  Looking at the school, spending, size, and type summaries prior to the update, there are drops in the scores.  School comparisons showed the most significant drop while the spending, size, and type summaries showed minimal drops.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7, Jupyter Notebook, Pandas library
