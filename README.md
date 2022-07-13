# school_district_analysis
## Overview & Scope of School Metrics Analysis
### Initial Analysis: Comprehensive Analysis
This project was undertaken to provide a comprehensive school district analysis across metrics for reading, math and overall success measured against school size, type and budget per student to the School District Board. The analysis will help reinforce statistics derived from math and reading scores across all grades for 38 district high schools and the results will help the school board drive decisions about predictors for success. 

After analysis was complete, the school board became aware of compromised data: specifically the reading and math scores for 9th graders at a participating high school needed to be nulled because of evidence of dishonesty in the reporting. The implications of omitting the polluted data are discussed in the results section as a comparison of before and after voiding the 9th grade scores of Thomas High School.

### Secondary Comparative Analysis: Excluding Polluted Data
A full analysis of the schools districts was delivered to the school board for review. Please see PyCitySchool_Challenge,ipyn in the resources folder for the full scipt run on the data. The second signifact deliverable to the school board was a comparative analysis of the success metrics including the statistics from the 9th graders at Thomas High School and the analysis excluding the compromised data. The school board was intent on knowing how much the polluted data impacted the results. Replacing the ninth graders' math and reading scores with "NaN" to void the scores resulted in the following changes:


## Results: Relative Impact Before & After Polluted/Compromised Data Removal
### District Summary Results
How is the district summary affected?
### School Summary Results
How is the school summary affected?
### Relative Performance Change Thomas High School
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
## How does replacing the ninth-grade scores affect the following:
### Math & Reading Scores by Grade
Math and reading scores by grade
### Scores by School Spending
Scores by school spending
### Scores by School Size
Scores by school size
### Scores by School Type
Scores by school type


Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:

The overall passing percentage for Thomas High School fell to 65%
The overall passing percentage for the entire district fell to 64.9%
Thomas High School was no longer included on the list of top five schools.
When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:

The overall passing percentages of Thomas High School decreased by 0.11%
The average scores of Thomas High School for math and reading increased by 0.06
For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.


## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


## Resources
Resources: All raw data files used in the analysis can be found inside of the resources folder.

Software: Python 3.7, Anaconda, Jupyter Notebook



