# School_District_Analysis

## Purpose of the Analysis
This analysis was ran to understand the performance trends across the school districts schools to make strategic and informed decisions on how funds and resources should be allocated across the district. The findings from this analysis will be used by members of the individual schoola and at the district level. The analysis uses test scores to maeasure sucess of students. The measure of sucess will be observed with school funding, school size, and school type as factors that drive sucess or passing masth and reading scores for students.

The student data used in this analysis contains data on each students grade, school and the scores they received in math and reading for the given standardized tests. And, the school data will contain information on the type of school, funding and size of the student body at the school. Using these two data sets the school board can view the trends on how the budget allotments impact sucess or passing scores for the standardized tests.

After taking into account the academic dishonesty for Thomas High School ninth graders we have ommitted them from the datasets to get a more clear picture of the trends for all the schools with valid test scores. The omission was made by changing all values of the Thomas High School math and reading scores to NaN's so they will not be accounted for in any of the below scenarios in our trend analysis of the school district.

## Results
### District Summary
After taking the Thomas High School ninth grade scores out of the analysis our average score has not changed much. Since the district summary takes the mathematical calculation of the averge passing grade of math and reading for each school and then calculates the average it does not create a shift, this is becuase the scores for Thomas High School ninth graders are close enough to the median and mean, so the omission of the value will not shift the values for the average math or reading scores. On this same notion, % passed is an aggregation of all the schools and since Thomas High School does not deviate far from the mean and median it does not create a significant difference on the broader trend.

### School Summary
Similarly the school summary did not see much of shift in trends as the values for the Thomas High School ninth grade math and reading scores were very much in line the scores of the other grades at the school. By removing the 9th grade scores, in the edited image, we can see the overall passing score for Thomas High School has dropped .32 percent which is not significant enough to shift the average of the Thomas High School in comparison to the unedited image. It not significant enough to move it up or down in ranking significantly. This means that even without the ninth grade scores, Thomas High School's valid test scores show no sigificant change if looking at school level data.

[School Summary Unedited](Resources/school_summary_unedited.PNG)

[School Summary Edited](Resources/school_summary_edited.PNG)

### Thomas High School
As the performance of ninth graders of Thomas High School were relatively similar to that of the other tenth thru twelfth graders at the shcool, the omission of the ninth graders did not shift the ranking, averages or the overall passing percentages for the school.

### Impacts of Thomas High School Ninth Grade Data Omission
#### Math and Reading Scores by Grade
By removing the ninth grade data for Thomas High School, it will not impact the other grades in how the averages or passing percentages are performed. Also, as stated above, the average scors for both math and reading for ninth graders at Thomas High School are close enough to the average it does not deviate significantly from the original analysis.

#### Scores by School Spending
As the scores did not pose a significant shift in averages it did not impact the spending by the scores for the schools. According to the edited and unedited spending summary, omitting the ninth grade scores did not shift the averages of the spendings at all to create a difference between the edited and unedited images. The omission of ninth grade data from Thomas high school did not show change in trends for the schools success in passing math or reading in asessing budget allocation at the school level.

[School Spending Unedited](Resources/spending_summary_unedited.PNG)

[School Spending Unedited](Resources/spending_summary_edited.PNG)

#### Scores by School Type
Taking the analysis for school type did not change the results from the unedited data to the edited data significantly to show a drastic change in the trends for the schools test score type in assessing budget allocation at the school type level.


## Summary
After analyzing the data with the omission of the Thomas High School ninth grade math and reading score data, ther were no observable changes in looking at the district level, school level, grade level or by the school type. Though the numbers do not change significantly by removing the invalid data, it should be noted when looking specifically at Thomas High School in the future.