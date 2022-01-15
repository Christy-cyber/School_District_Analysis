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
Evidence of academic dishonesty was found for 9th grade reading and math scores at Thomas High School.  In order to uphold state testing standards, a reevaluation of the metrics was performed.  Ninth grade reading and math scores at Thomas High School were subsequently replaced with "Not a Number" (NaN) and the metrics and deliverables were recalculated and reconstructed, respectively.  Results shown below indicate the original and updated metrics once the scores were replaced.


## Resources
- Data Sources: schools_complete.csv, students_complete.csv
- Software and Programming Languages: Jupyter Notebook v. 6.4.6; Python v. 3.8.3 :: Anaconda, Inc.; conda v. 4.11.0


## Results
The following results address findings using original metric data and metrics calculated after 9th grade scores were changed to "NaN" at Thomas High School:

- District Summary
  - The district summary shows values for percent passing math, percent passing reading, and percent overall passing were around 75%, 85%, and 65%, respectively, after 9th grade scores were changed to "NaN" (Table 1).

Table 1.  District summary based on revised metrics.
![District Analysis Revised--summary](https://user-images.githubusercontent.com/95387273/149626344-ea750750-170e-4010-b27a-c5b9b5633bfc.png)


- School Summary
  - The school summary for Thomas High School showed pronounced changes after 9th grade math and reading scores were changed to "NaN".   Original metric data showed scores for average math score (83), average reading score (83), percent passing math (66%), percent passing reading (69%), and percent overall passing (65%) were lower than metrics calculated after scores were changed.  Updated metrics show the average math (83) and average reading (83) scores remained unchanged, but percent passing math (93%), percent passing reading (97%), and percent overall passing (90%) values were around 25 to 30 percentage points higher (Tables 2 and 3).

Table 2.  School summary for Thomas High School based on original metrics.
![School summary original heading](https://user-images.githubusercontent.com/95387273/149624979-ab19b8dd-9aba-4775-afc9-6a63e8831606.png)
![School summary original--Thomas only](https://user-images.githubusercontent.com/95387273/149624985-94bcb2e9-ed21-45b3-bf23-b3b6ecc179c6.png)

Table 3.  School summary for Thomas High School based on updated metrics after ninth grade scores were replaced.
![School summary original heading](https://user-images.githubusercontent.com/95387273/149625060-c5419d69-a2f9-4b3d-94ac-288d31f0f271.png)
![school summary revised--Thomas only](https://user-images.githubusercontent.com/95387273/149625067-bc7759e4-f5b3-4eac-b8e8-a8ce53d9b4ad.png)



- High and Low Performing Schools
  - Thomas High School ranks in the top five high schools in the district based on percent of students passing math, percent passing reading, and percent overall passing, based on the new metrics.  The original metrics presented above in "School Summary" above show that Thomas High School would have ranked much lower before 9th grade scores were changed (Table 4). 

Table 4. Top five performing schools based on updated metrics.
![Top  five schools revised](https://user-images.githubusercontent.com/95387273/149625157-3590c570-65a1-464a-b657-3b9fbb1b093b.png)


- Math and Reading Scores by Grade
  - Average math and reading scores by grade remained unchanged across all schools.  The only exceptions were the 9th grade reading and math scores at Thomas High School that were changed to "Nan".

- Scores by Per Capita Spending
  - Thomas High School spends $630.00 - $644.00 per student. At this range of per capita spending, the original metrics would have shown lower passing percentage rates than what the updated metrics show.  The updated metrics indicate percent passing math, percent passing reading, and percent overall passing at 73%, 84%, and 63%, respectively, for this spending bracket (Table 5).

Table 5.  Student passing rates per spending per capita based on updated metrics
![spending summary revised](https://user-images.githubusercontent.com/95387273/149625307-160b6ef8-239d-4d7b-b6bb-039f47f0c9c9.png)


- Scores by School Size
  - Thomas High School is a charter school of medium size (about 1600 students).  Original data metrics would have shown that the percent passing math, percent passing reading, and percent overall passing scores for medium size schools would be lower than what are shown in the updated metrics, which are 94%, 97%, and 91%, respectively (Table 6).  Medium and small size schools have the highest passing rates for both reading and math.

Table 6.  Student passing rates per school size based on updated metrics.
![school size revised](https://user-images.githubusercontent.com/95387273/149625460-6a44e2ba-eaac-4a9b-82c8-85f07d3f189a.png)


- Scores by School Type
  - Updated metrics show that students at charter schools outperform students at district schools for percent passing math, percent passing reading, and perent overall passing (94%, 97%, and 90%, respectively).  These values would have been lower in the original metrics (Table 7).

Table 7.  Student passing rates per school type based on updated metrics.
![school type revised](https://user-images.githubusercontent.com/95387273/149625619-fbb05122-1652-4fcb-a7d4-705770163b19.png)



## Summary
### Findings after Reevaluation of the Metrics
The following were noted with regards to the School District Analysis after reevaluation of the the metrics once the reading and math scores for 9th grade students at Thomas High School were replaced with "NaN":
- School metrics for Thomas High School increased 25-30 percentage points for percent passing math, percent passing reading, and percent overall passing while average math and reading scores remained the same.
- Average math and reading scores by grade remained unchanged across the district, except for the 9th grade scores at Thomas High School that were changed to "NaN."
- Thomas High School ranks in the top five performing schools in the district.
- Medium and small sized schools have the highest passing rates in math and reading.

### Interpretation of Findings
Based on the updated metrics, the highest performing students:
- attended charter schools
- attended schools that were categorized as small (< 1000 students) or medium (1000-1999 students) in size
- attended schools that spent the least amount per capita (schools that spent $585.00 - $629.00 per student followed by < $584.00 per student)

The lowest performing students:
- attended district schools
- attended schools that were categorized as large (2000-5000 students) in size
- attended schools that spent the most amount per capita (schools that spent $645.00 - $675.00 per student)

These findings suggest that school size most likely has the greatest impact on student success rates in reading and math.  Even though the top five highest performing schools were charter schools, they were all small in size, whereas the top five lowest performing schools were all large in population size.  The lowest performing schools happened to be large district schools.  Additionally, these findings indicate that an increase in per capita spending would not necessarily result in higher test scores.  Schools that spent the least per capita in this district had the highest performing students.  This can be explained by the budget size of large and small schools.  Small schools have smaller budgets so spend less per student, whereas large schools have larger budgets so spend more per student on average. District leaders should focus on reducing school population sizes to less than 2000 students in order to develop students who are successful in math and reading.
