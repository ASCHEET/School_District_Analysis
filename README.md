# School_District_Analysis
## Using python and anaconda and junyper

## Overview of the school district analysis: Explain the purpose of this analysis.
### The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
### Due to the potential grades of the Thomas High School freshman being compromised the grades were omitted from secondary analysis and compared to the original to determine its affects on results.

How is the district summary affected?
### With the Thomas High School freshman class removed from the analysis the district numbers drop slightly:
### The % Passing Math decreases from 75.0 to 74.8; % Reading Scores decreases from 85.8 to 85.7, and % Overall Passing decreased from 65.2 to 64.9.  Upon initial glance Thomas High School freshman had fairly high grades; this makes sense if it is a Charter School.
[pic of district_summary_all]
[pic of district_summary_notall]

### The school summary is affected significantly removing the freshman class math and reading from Thomas High School totals.  This is mainly due to the scores being removed by the student's numbers being kept messing up the averages for the percentages.  Prior to the student number correction; the % Passing Math was 66.9% but the average Math Score was 83.4.  Similarly, with the % Passing Reading was 69.7% but the average reading score was 83.9.  
[school summary all]
### Therefore; when the numbers for the analysis are adjusted so the freshman students are not included in the percentage calculations the % Passing Math Increases from 66.9% to 93.2%, and % Passing Reading increases from 69.7% to 97%
[school summary not all]

### Properly adjusting these figures places Thomas High School into the top 5 performing schools when the freshman class is properly removed from the analysis.  

### Replacing the freshman scores at Thomas High School does not affect the math and reading scores by grade (except for the NaN value). 
[per_grade_math]
[per_grade_reading]
### Scores by school spending, scores by school size, and scores by type are not affected because the students are still students there and still counted for those analysis.  If the analysis was based on cost per grade, then a separate analysis could be performed based on the cost of each grade submitted.  Thomas High School did spend $638 per student, but actually it was $930 per student that passed math and reading successfully.

