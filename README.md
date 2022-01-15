# School District Analysis
## Overview of School District Analysis
### Metrics
Budgetary data along with reading and math scores were analyzed for 9th-12th graders at 15 high schools in this educational district.  The following metrics were requested:
- Total budget per school
- Per student budget
- Average math scores
- Average reading scores
- Percent of students passing math >= 70
- Percent of students passing reading >= 70
- Percent of students passing both math and reading >= 70

### Deliverables
The following deliverables were requested based on the metrics calculated above:
 - Metrics by district
 - Metrics by school
 - Metrics by top five highest and lowest performing schools
 - Average math and reading scores by grade for each school
 - Math and reading scores, and percent of students passing, by per capita spending
 - Math and reading scores, and percent of students passing, by school size
 - Math and reading scores, and percent of students passing, by school type (district vs. charter)

### Reevaluation of the Metrics
Evidence of academic dishonesty was found for 9th grade reading and math scores at Thomas High School.  In order to uphold state testing standards, a reevaluation of the metrics was performed.  Ninth grade reading and math scores at Thomas High School were subsequently replaced with "Not a Number" (NaN) and the metrics and deliverables were recalculated and reconstructed, respectively.  Results shown below indicate the before and after findings once the scores were replaced.


## Resources
- Data Sources: schools_complete.csv, students_complete.csv
- Software and Programming Languages: Jupyter Notebook v. 6.4.6; Python v. 3.8.3 :: Anaconda, Inc.; conda v. 4.11.0


## Results
The following results address findings using original metric data and metrics calculated after 9th grade scores were changed to "NaN" at Thomas High School:

- District Summary
  - The district summary remained relatively unchanged before and after math and reading scores were changed to "NaN".  Values for percent passing math, percent passing reading, and percent overall passing were around 75%, 85%, and 65%, respectively, in both instances.

- School Summary
  - The school summary for Thomas High School showed pronounced changes after 9th grade math and reading scores were changed to "NaN".   Original metric data showed scores for average math score (83), average reading score (83), percent passing math (66%), percent passing reading (69%), and percent overall passing (65%) were lower than metrics calculated after scores were changed.  Updated metrics show the average math (83) and average reading (83) scores remained unchanged, but percent passing math (93%), percent passing reading (97%), and percent overall passing (90%) values were around 25 to 30 percentage points higher.

- High and Low Performing Schools
  - Thomas High School ranks in the top five high schools in the district based on percent of students passing math, percent passing reading, and percent overall passing, based on the new metrics.  The original metrics presented above in "School Summary" showed that Thomas High School would have ranked much lower before 9th grade scores were changed. 

- Math and Reading Scores by Grade
  - Average math and reading scores by grade remained unchanged across all schools.  The only exceptions were the 9th grade reading and math scores at Thomas High School that were changed to "Nan".

- Scores by Per Capita Spending
  - Thomas High School spends $630.00 - $644.00 per student. At this range of per capita spending, the original metrics would have shown lower passing percentage rates than what the updated metrics show.  The updated metrics indicate percent passing math, percent passing reading, and percent overall passing at 73%, 84%, and 63%, respectively.

- Scores by School Size
  - Thomas High School is a charter school of medium size (about 1600 students).  Original data metrics would have shown that the percent passing math, percent passing reading, and percent overall passing scores for medium size schools would be lower than what are shown in the updated metrics, which are 94%, 97%, and 91%, respectively.  

- Scores by School Type
  - Updated metrics show that students at charter schools outperform students at district schools for percent passing math, percent passing reading, and perent overall passing (94%, 97%, and 90%, respectively).  These values would have been lower in the original metrics.


## Summary
### Findings after Reevaluation of the Metrics
The following were noted with regards to the School District Analysis after reevaluation of the the metrics once the reading and math scores for 9th grade students at Thomas High School were replaced with "NaN":
- Overall, average math and reading scores and percent passing rates at the district level remained relatively unchanged.
- School metrics for Thomas High School increased 25-30 percentage points for percent passing math, percent passing reading, and percent overall passing while average math and reading scores remained the same.
- Average math and reading scores by grade remained unchanged across the district, except for the 9th grade scores at Thomas High School that were changed to "NaN."
- Thomas High School ranks in the top five performing schools in the district.

### Interpretation of Findings
Based on the updated metrics, the highest performing students:
- attended charter schools
- attended schools that were categorized as small (< 1000 students) or medium (1000-1999 students) in size
- attended schools that spent the least amount per capita (schools that spent $584.00 per student followed by those that spent $585.00 - $629.00 per student)

The lowest performing students:
- attended district schools
- attended schools that were categorized as large (2000-5000 students) in size
- attended schools that spent the most amount per capita (schools that spent $645.00 - $675.00 per student

These findings suggest that school size most likely has the greatest impact on student success rates in reading and math.  Even though the top five highest performing schools were charter schools, they were all small in size, whereas the top five lowest performing schools were all large in population size.  The lowest performing schools happened to be large district schools.  Additionally, these findings indicate that an increase in per capita spending would not necessarily result in better test scores.  Schools that spent the least per capita in this district had the highest performing students.  This can be explained by the budget size of large and small schools.  Small schools have smaller budgets so spend less per student, whereas large schools have larger budgets so spend more per student. District leaders should focus on reducing school population sizes to less than 2000 students in order to develop students who are successful in math and reading.
