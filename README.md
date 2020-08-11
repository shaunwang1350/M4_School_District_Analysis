# School_District_Analysis
## Summary

In this project, we were asked to analyze and process data about a sample of high schools and their performance. We looked at the reading, math and overal passing percentages for each school, sorting by School Type (District / Charter), Spending Bins Per School, Grouping by Spending Ranges, and Categorizing by Grade Level. As well as, creating a district and school summary for all of the data. The challenge was to eliminate the Thomas High School's 9th grade student's scores and see its effects on the overal data and summaries.

## Procedure 
1. Imported modules needed and setting up file_to_open paths¶
2. Corrected the students' names so there are no professional prefixes or suffixes
3. Replaced the reading and math scores for ninth graders at Thomas High School with NaN.
4. Merged the clean student data with the school dataset, where the column order for all the DataFrames and number are formatted.
5. Recreated the district and school summary DataFrames
6. Created a District Summary and School Summary
7. Recalculated the high- and low-performing schools, Analyzed the top 5 schools
8. Recalculated the scores by grade, scores by school spending, scores by school size, and scores by school type.
9. Created a DataFrame on Effects of Ninth-grade Scores: Math and Reading Scores by Grade
10. Created a DataFrame on Effects of Ninth-grade Scores: Scores by School Spending
11. Created a DataFrame on Effects of Ninth-grade Scores: Scores School Size
12. Created a DataFrame on Effects of Ninth-grade Scores: Socres by School Type

## Findings
* With the 9th grade scores of THS eliminated, the overall passing percentage dropped from 64.09% to 65.17%. This also means that the average math score droped from 79 to 78.9, and the % of students passing math also dropeed from 74.98% to 85.81%. That said, while % of students passing reading dropped from 85.81% to 84.65%, the average reading score remained the same at 81.9.
* Previously, Thomas High School was second in terms of all of the tops school. It had an average math score of 83.42%, an average reading score of 83.85%, and with % in Passing math and reading in 93.27% and 97.31% respectively. Overall, it used to have 90.95% passing. With the 9th grade scores eliminated, it is no longer a top-five school.
* Since we deleted data for THS's 9th grade reading and math scores, it shows up as NaN. However, this does not affect other data in this composite viewer across all schools for each grade.
* With the 9th grade scores of THS eliminated, the percentages within spending range 630-644 shifted the most. With the average math score, percentage of students passing math and percentage of students passing reading lowered, it resulted with a lower overall passing percentage for the spending 630-644 spending range.
* With the 9th grade scores of THS eliminated, it seems that it has dramatically lowered the medium school size overall passing percentage, from 90.62% to 85.45%. This comes with the reduction of average math score, average reading score and the percentage of students passing math and reading.
* With the 9th grade scores of THS eliminated, the average math score, % of students passing math, % of students passing, and overal passing percentage all droped for charter school type. With one exception, it seems the average reading score for remained the same.

## Notes
*The section below school summary is commentated out because if formatting is applied to this Dataframe, there will be a KeyError in calling these variables again.
