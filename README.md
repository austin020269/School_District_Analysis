# School_District_Analysis

## Project Overview
The school has provided data to analyze school spending and standardized test scores.

## Resources
Data Sources provided to analyze and minipulate included:
- schools_complete.csv
- students_complete.csv
- clean_students_complete.csv
- missing_grades.csv

Software utilized for this study included: 
- Python 3.7.6 
- Conda 4.9.2 
- Jupyter Notebook 6.1.4

## Analysis and Workflow
Data for the math and reading scores were removed then we created a new dataframe consisting of the district and school summaries to maipulte the following:

- Top 5 and bottom 5 performing schools.
- Average math score received by students in each grade level at each school.
- Average reading score received by students in each grade level at each school.
- School performance based on the spending per student.
- School performance based on the size of the school.
- School performance based on the type of school.

The Jupyter notebooks (Python code) for the above analysis can be found here:

https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools.ipynb
https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools_Challenge_testing.ipynb

## Summary
✓ How is the district summary affected?
The average math score decreased by 0.1 points while the average reading score stayed the same. The percentage of students passing math decreased by 1% as did the percentage of students passing reading. The overall passing percentage also decreased by 1%.

✓ How is the school summary affected?
The only change in data is with Thomas High School. The overall math and reading passing numbers decreased.

✓ How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
Thomas High School moved from 2nd place overall with a passing % of ~92% down to last place with a passing % of ~68%.

✓ How does removing the ninth grade scores affect the following?

Math and Reading Scores by Grade
Thomas High School's 9th grade class has no math or reading score data to count. Everything else was unaffected.

Scores by School Spending
The $630-644 bin saw a decrease in the passing percentages since Thomas High School was in that spending range. Though, interestingly the average math and reading scores for that range remained the same.

Scores by School Size
The Medium (1000-2000) bin saw a decrease in the passing percentages since Thomas High School was in that school size. Though, interestingly the average math and reading scores for that range remained the same.

Scores by School Type
The Charter schools saw a decrease in the passing percentages since Thomas High School was in that school type. Though, interestingly the average math and reading scores for that range remained the same.
