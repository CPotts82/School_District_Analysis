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

- By replacing the 9th grade scores for reading and math at Thomas High School with NaN, it affected performance relative to other schools by:

#### Thomas High School 
- Replacing the 9th grade math/reading scores at Thomas High School affected:
  - The Average Math Score for the school (minus the 9th grade) dropped from 83.42 to 83.35.
  - The Average Reading Score for the school (minus 9th grade) actually increased from 83.85 to 83.90.
  - Percent Passing Math decreased from 93.27% to 93.19%.
  - Percent Passing Reading decreased from 97.31% to 97.02%.
  - The Overall Passing Percent decreased from an initial 90.95% to 90.63%.

### Scores by Spending, Size and Type:
  - Scores by school spending by:
    - This parameter was not affected
  - Scores by school size by:
    - This parameter was not affected
  - Scores by school type by:
    - This parameter was not affected

## Summary 
1- q
2- 
3- 
4- 
