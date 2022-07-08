# School_District_Analysis
## Project Overview
The focus of this analysis was to examine the standardized reading and math scores among high school students from 15 different schools in the same district.  The objective was to analyze trends in student performance to see how this relates to budget allowance per student. This analysis will be used by the school board and administration to make future budgeting decisions.  After the initial analysis was completed, an inconsistency pertaining to the math and reading scores for Thomas High School's ninth grade class caused those scores to be completely removed from the dataset.  The school district analysis was re-run without the scores for Thomas High School's ninth grade class.  The results of the second analysis will be discussed in this report along with comparisons from the initial report.

## Resources
Data Source: schools_complete.csv and students_complete.csv.  
Software: Python 3.7.6, Anaconda - Jupyter Notebook

## Results
### District Summary 
- The District Summary was affected in the following ways:
  - The number of students taken into account in the second analysis fell from 39,170 to 38,709 students.  There were 461 ninth grade students at Thomas High School and those students have been removed from the total student count.  This will affect some of the calculations.
  - The Average Math Score is now 78.9 having dropped .1 points from the initial analysis.  
  - The Percentage of Students passing Math also dropped .2 points, it is now a 74.8%.
  - The Percent of Students Passing Reading dropped .1 points, it is now 85.7%.
  - The Overall Passing Percentage also dropped .3 points.  It was at a 65.2% and is now a 64.9%.

### School Summary
- The School Summary was affected in the following ways:
  - The only aspect of the school summary that was affected was Thomas High School's scores. The other school's averages for math and reading as well as passing percentages for math, reading and overall passing remained the same.  If there was any change in the calculations due to the change in total student count, it was so minimal that it was not seen in the formatted data. 
#### Thomas High School 
- Replacing the 9th grade math/reading scores at Thomas High School affected:
  - The Average Math Score for the school (minus the 9th grade) dropped from 83.42 to 83.35.
  - The Average Reading Score for the school (minus 9th grade) actually increased from 83.85 to 83.90.
  - Percent Passing Math decreased from 93.27% to 93.19%.
  - Percent Passing Reading decreased from 97.31% to 97.02%.
  - The Overall Passing Percent decreased from an initial 90.95% to 90.63%.
- By replacing the 9th grade scores for reading and math at Thomas High School with NaN, it affected performance relative to other schools by:
  - It did not have an impact on how Thomas High School performed compared to other schools.  Thomas High School still ranked second in Overall Passing Percentage compared to the other schools.  Thomas High School ranked #2 in the top schools for student overall performance in the standardized testing for math and reading scores. 
### Scores by Spending, Size and Type:
  - Scores by school spending were affected by:
    - The new analysis did not effect the results of the initial analysis for spending per student.  The analysis showed that the schools with a budget of less than $586 per student had the highest performance in all categories.
  - Scores by school size were affected by:
    - The new analysis did not show a change in school performance based on school size. The initial analysis showed that the smaller and medium size school populations performed better in all categories compared to the large population schools.
  - Scores by school type were afffected by:
    - The new analysis did not change the output from this analysis.  The initial analysis showed that the Charter schools performed better than the district schools in all categories. The performance of students at Charter schools was much higher in the percent passing math category and the overall passing percentage. 

## Summary 
The main ways that the school district analysis was impacted by the change in Thomas High School ninth grade scores for reading and math being changed to NaN; was in the district summary as well as by affecting Thomas High School's scores directly.  It only makes sense that some calculations were impacted because the overall total student count for all 15 schools decreased by 461.  The District Summary was most effected because this change in total student count affected all three percentage calculations.  The % passing math decreased by .2 points, the percent passing reading decreased by .1 points and the overall percent passing decreased .3 points. 
For Thomas High School the decrease in their student count directly affected the percentage calculations.  The percent passing math and reading both dropped as well as the overall passing percent.  Surprisingly the average reading score increased by .05%.  The second analysis without the ninth grade scores from Thomas High did affect some areas but really did not affect too many aspects of this analysis because 461 students is really not much compared to over 38,000 students in total. 
