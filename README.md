# school_district_analysis
## Overview & Scope of School Metrics Analysis
### Initial Analysis: Comprehensive Analysis
This project was undertaken to provide a comprehensive school district analysis across metrics for reading, math and overall success measured against school size, type and budget per student to the School District Board. The analysis will help reinforce statistics derived from math and reading scores across all grades for 15 district high schools and the results will help the school board drive decisions about predictors for success. 

After analysis was complete, the school board became aware of compromised data: specifically the reading and math scores for 9th graders at Thomas High School (THS) needed to be nulled because of evidence of dishonesty in the reporting. The implications of omitting the polluted data are discussed in the results section as a comparison of before and after voiding the 9th grade scores of Thomas High School.

### Secondary Comparative Analysis: Excluding Compromised Data
A full analysis of the schools districts was delivered to the school board for review. Please see PyCitySchool_Challenge,ipyn in the resources folder for the full scipt run on the data. The second signifact deliverable to the school board was a comparative analysis of the success metrics including the statistics from the 9th graders at THS and the analysis excluding the compromised data. The school board was intent on knowing how much the polluted data impacted the results. Replacing the ninth graders' math and reading scores with "NaN" to void the scores resulted in the following changes:


## Results: Relative Impact Before & After Polluted/Compromised Data Removal
### Thomas High School Summary Results

![school_summary_after](https://user-images.githubusercontent.com/107326987/178653578-a9d43f6f-469b-4634-a7dd-be4b9d5b86e3.png)

The overall metrics for THS were negligably affected by ommitting the data from the 9th grade reading and writing scores. Originally % Passing Math, % Passing Reading and % Overall Passing were 93.2%	97.3%	90.9% respectively. In the absence of the 9th grade scores, these data points are 93.2%, 97.0% and 90.6% respectively. Across these three data points the most significant change was +/-0.3%. While the 9th grade data may not have had integrity, it was relatively consistent with the rest of the dataset. The 9th grade data was not holding THS's performance metrics artifically low or high.

### Relative Performance Change Thomas High School
The impact of ommitting the compromised data was negligible on THS's statistics singularly. Consequently, it did not impact the relative standing of the high school aginst rankings of other schools. When the schools are sorted by ascending order of "% Overall Passing" - a measurement of averages of reading and math scores, their standing remains 2nd. The 0.3% decrease in THS's overall passing % was not large enough to move the needle on their comparative standing.

![thomas_relative_performance_no9](https://user-images.githubusercontent.com/107326987/178653808-d7034a3f-1240-42a9-bf54-811d294bfbd4.png)

### District Summary Results

Outside of the relatively small changes in the singular metrics of THS (reading, math, and overall passing) and their relative perfomance to other schools in the district - removing the compromised data of the 9th grade class of Thomas High School had little to no impact on the district wide summaries. The metrics for the district summary were unchanged when measured to the 10th of a percent as seen below.

![district_summary_after](https://user-images.githubusercontent.com/107326987/178653467-73046a09-1571-4c5a-8e74-b85a81986354.png)

### District Math & Reading Scores by Grade
![math_by_school_after](https://user-images.githubusercontent.com/107326987/178653850-ed48d9be-da4d-43b9-970c-0a562f92e2d7.png)
![reading_by_school_after](https://user-images.githubusercontent.com/107326987/178653866-937efff1-31dc-4221-8714-387d51428ca4.png)
The first and second image reflect the math and reading averages per grade per school after ommitting THS 9th grade scores. These metrics remain unchanged as they are teased apart by school and by grade, here you are able to see the value "NaN" in place of the score for THS, grade 9 in both math and reading.

### Scores by School Spending
![school_spending_before](https://user-images.githubusercontent.com/107326987/178660425-57f80450-7298-4baf-9fe2-ec36935a403b.png)
Any reflection points here?
There is no noticeable impact on the metrics when measured to the .1% of spending based on avg. scores.
### Scores by School Size
![scores_by_size_after](https://user-images.githubusercontent.com/107326987/178653984-01070d73-a9b9-4499-84ec-34648d079f3c.png)
Any reflection points here?
There is no noticeable impact on the metrics when measured to the .1% of school sized based on avg. scores.
### Scores by School Type
![scores_by_type_after](https://user-images.githubusercontent.com/107326987/178653949-e38d66af-fe1c-4dde-b743-3f1b1d87ce33.png)
Any reflection points here?
There is no noticeable impact on the metrics when measured to the .1% of school type based on avg. scores.


## Summary: 
In order to maintain state grading standards and make the school district data compatable/comparable with other school district data for larger data sets and more analysis, it was important to voide the values for the compromised data. While the 9th grade scores from THS cannot be used, their ommission has little impact on our results. This can give the project confidence that the analyis in the absence of our dataset has integrity. The conclusions from the district wide summaries remain enforced. List some here. The impact of the polluted data was prescribed exclusively to THS results, and even then the greatst variance in comparison tobefore and after was 0.3%. We saw this play out on the individual  oSummarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


## Resources
Resources: All raw data files used in the analysis can be found inside of the resources folder.

Software: Python 3.7, Anaconda, Jupyter Notebook



