# School_District_Analysis

## Purpose
Maria, the chief data analyst for a city school was asked to analyse the standardize test data in order to help make strategic decisions regarding the schools. Our job was to assist Maria by helping organize the raw data sets that were given to us by the school board. The first thing we had to do was to clean up the data sets for any null values or any issues like accidental prefixes in the name. Next we made calculation that would help the schools like budget per student and percentage of student that passed the reading and math section as well as formatting the data to make it presentable for the meeting. We were also able to assist Maria during her meeting by making more data frames during the meeting to help those who attended with their decision making. Unfortunatly, after the meeting it was discovered that an entire grade from one school was caught cheating and so the work had to be redone with their results being taken out.

## Results
####	In the District Summary
  
   •	Average Reading Score stayed the same, 

   • Average Math Score decreased by 0.1, 

   • % Passing Math decreased by 0.2

   • % Passing Reading decreased by 0.3

   • % Overall Passing decreased by 0.1
### Original District Summary
![image](https://user-images.githubusercontent.com/76131315/105649022-6cd84300-5e7c-11eb-90c2-5eb55e10c677.png)
### New District Summary
![image](https://user-images.githubusercontent.com/76131315/105649045-88dbe480-5e7c-11eb-87c6-e14e530e09b1.png)

####	In the Per School Summary the only change is the row for Thomas High School where

• Average Math Score decreased by 0.067412

• Average Reading Score increased by 0.047152

•	% Passing Math decreased by 0.086481
  
• % Passing Reading decreased by 0.29013
  
•	% Overall Passing decreased by 0.317688

• These changes do not affect Thomas High School much as they are still in the 90 Percentile as well as still being in the top 5 for Overall Passing Percentage. 	
#### Original School Summary
![image](https://user-images.githubusercontent.com/76131315/105650456-c98a2c80-5e81-11eb-9fd3-34dc090dbc75.png)
#### New School Summary
![image](https://user-images.githubusercontent.com/76131315/105649696-3fd95f80-5e7f-11eb-920f-456df165dea8.png)

•	For Math and reading scorces by grade did not change aside from the fact that Thomas High School has nan for their 9th grade coloumns.

•	Scores by school spending there also were no changes in the averages by school spending

•	Scores by school size were not changed as well

•	Scores by school type were also not affected by the removal of the 9th graders from Thomas High School

## Summary

By Removing the marks for the Thomas High School 9th graders, we saw that Thomas High School saw their average math score decrease by a minimal amount, 0.067412 to be percise, as well as the percentage who pased math went down by 0.086481. The relative change in the math and reading averges by grade was also expected as on the Thomas High School 9th graders' marks were set to nan so their coloumn should say nan while everyone elses should have remained the same as they were untouched. Lastly, there was no changes school spending as Thomas High School was in the same bracket in spending as that did not change, and while the Thomas averages and percentage passed change, the changes were so marginal that added with the other in their spending range their averages saw no change.
