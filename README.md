# School_District_Analysis

## Overview of School District Analysis

Because of evidence of academic dishonesty in the district, it appears that the scores for ninth-grade students who attend Thomas High School have been altered. The school board has asked that the scores for 9th grade reading and math be dropped for Thomas High School, but that the remainder of the data should stay the same. The analysis in this project will compare the original data for the district to the revised district data which does not include these scores. The project will describe the changes in the overall analysis.

## Results of School District Analysis

Bulleted list that addresses how each of the 7 school district metrics were affected by changes in data.
* How is the school summary affected?
	**The school district data overall dropped slightly by removing the 9th-grade scores for reading and math for Thomas High School.**
	- **Original Data**
		- Average Math Score, 79.0%
		- Average Reading Score, 81.9%
		- % Passing Math, 75.0%
		- % Passing Reading, 85.8%
		- % Overall Passing, 65.2%
	- **New Data**
		- Average Math Score, 78.9% 
		- Average Reading Score, 81.9%
		- % Passing Math, 74.8%
		- % Passing Reading, 85.7%
		- % Overall Passing, 64.9%
		**Note:** The school district data overall dropped slightly by removing the 9th-grade scores for reading and math for Thomas High School.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	- **Original Data for Thomas High School**
		Average Math Score, 83.4
		Average Reading Score, 83.8
		% Passing Math, 93.3%
		% Passing Reading, 97.3%
		Overall Passing 90.9%
		Only one school had a higher overall % passing score.
	- **New Data for Thomas High School**
		Average Math Score, 83.4
		Average Reading Score, 83.9
		% Passing Math, 93.2%
		% Passing Reading, 97.0%
		Overall Passing 90.6%
		**Note:** Thomas High School's ranking did not change compared to other high schools in terms of higher overall % passing score. The overall passing score dropped only 0.3 percent compared to other schools. This is because the students in 10th to 12th grade still performed well. Their average scores were included in the overall ranking, while the 9th grade students scores did not figure into this score.
* How does replacing the ninth-grade scores affect the following:
	- **Math and reading scores by grade**
		**Note:** No individual grade-level scores were affected other than for 9th-grade students at Thomas High School. Since the data was removed for these students, the summary for these students is null (NaN). All other scores remain the same. 
	- **Scores by school spending**
		- **Original Data ($630-644)**
		Average Math Score, 78.5
		Average Reading Score, 81.6
		% Passing Math, 74%
		% Passing Reading, 84%
		Overall Passing 63%
		- **New Data ($630-644)**
		Average Math Score, 79.1
		Average Reading Score, 81.9
		% Passing Math, 76%
		% Passing Reading, 86%
		Overall Passing 66%
		**Note:** Because Thomas High School is in the $630-644 range for spending, only that range was affected by the change in student data. All scores increased slightly for that segment.
	- Scores by school size
		- **Original Data (Medium (1000-2000))**
		Average Math Score, 83.4
		Average Reading Score, 83.9
		% Passing Math, 94%
		% Passing Reading, 97%
		Overall Passing 91%
		- **New Data (Medium (1000-2000))**
		Average Math Score, 83.4
		Average Reading Score, 83.9
		% Passing Math, 94%
		% Passing Reading, 97%
		Overall Passing 91%
		**Note:** Thomas High School is in the Medium size (1000-2000) group. The scores stayed the same for the size group. 
	- Scores by school type
		- **Original Data (Charter)**
		Average Math Score, 83.5
		Average Reading Score, 83.9
		% Passing Math, 94%
		% Passing Reading, 97%
		Overall Passing, 90%
		- **New Data (Charter)**
		Average Math Score, 83.5
		Average Reading Score, 83.9
		% Passing Math, 94%
		% Passing Reading, 97%
		Overall Passing 90%
		**Note:** Thomas High School is in the Charter school group. The scores stayed the same for this group.

## Summary of School District Analysis

The changes to the school district analysis after the reading and math scores were replaced did little to change the overall averages for the analysis. The district average math score dropped slightly, going from 79.0% to 78.9% once the 9th grade math data from Thomas High School was removed. The % Passing Math for the district also dropped slightly, from the original value of 75.0% to 74.8%. The district summary for % Passing Reading dropped from 85.8% to 85.7%. The % Overall Passing Reading for the district also dropped slightly, from 65.2% originally to 64.9% after the 9th grade student data from Thomas High School was removed. The changes were small because the percent of 9th grade students for the overall district count was only 1.2%. By replacing the values for the average student math and replacing and the overall % reading scores for Thomas High School with the 10th to 12th grade scores and not including the counts for 9th grade students as 0 in the overall average for Thomas High School, their percentages only changed slightly. The ranking for Thomas High School stayed the same, again because the values for the 9th grade students were not included in the scores.
