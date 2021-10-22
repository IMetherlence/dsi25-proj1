## Project 1

This data analysis is presented to the students maximising their chances of scoring an appropriate grade on their ACT/SAT examinations to get into college.

**Sources:**

* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State

* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State

* [`sat_act_by_college.csv`](./data/sat_act_by_college.csv): Ranges of Accepted ACT & SAT Student Scores by Colleges


**Further Research:**

Understanding Your Scores : https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html

Interpret Your SAT Scores: https://collegereadiness.collegeboard.org/sat

ACT and SAT scores no longer required for admissions at some colleges: https://www.cbsnews.com/news/act-and-sat-no-longer-required-college-admissions/


|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*string*|ACT 2019 and SAT 2019|The state which students took the ACT exam|
|**participation**|*float*|ACT 2019 and SAT 2019|Percentage of eligible students (In high school) who took ACT|
|**composite**|*float*|ACT 2019 and SAT 2019|Average Composite Score of students who took ACT 2019 in the state|
|**weighted_act_comp**|*float*|ACT 2019 and SAT 2019|Percentage score of students' ACT composite results|
|**weighted_sat_comp**|*float*|ACT 2019 and SAT 2019|Percentage score of students' SAT total score results|
|**overall_grade_weight**|*float*|ACT 2019 and SAT 2019|The state which students took the ACT exam|

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**school**|*string*|SAT and ACT by College|Name of the school|
|**test_optional?**|*boolean*|SAT and ACT by College|Indicates if the school has optional ACT or SAT requirements|
|**number_of_applicants**|*integer*|SAT and ACT by College|Total number of applicants to the school|
|**accept_rate**|*float*|SAT and ACT by College|The percentage of students accepted to the school|
|**sat_25th_percentile**|*float*|SAT and ACT by College|25th percentile total score of all students applying with SAT examination results|
|**sat_75th_percentile**|*float*|SAT and ACT by College|75th percentile of total score all students applying with SAT examination results|
|**act_25th_percentile**|*float*|SAT and ACT by College|25th percentile of composite score all students applying with ACT examination results|
|**act_75th_percentile**|*float*|SAT and ACT by College|75th percentile of composite score all students applying with ACT examination results|

**Conclusion and Recommendations:**


Many universities are shifting away from the standard ACT and SAT examination criteria and moving more towards other means of admissions. Thus it is advisable to students not to solely focus on SAT and ACT exams but to focus on their co-curricular activities and projects as well. 

Also note that ACT and SAT are not the sole factor to admission into colleges as several are dropping them as a requirement due to COVID-19, as well as because colleges do not believe that ACT and SAT tests are good predictors to how well a student does.

It is recommended that students take either ACT or SAT examination instead of attempting both ACT and SAT examinations.

Location wise it may be better to move towards locations near the Ivy League colleges (Massachusetts, Minnesota, South Dakota) as these states have a higher scoring grade compared to other states. This is likely due to differences in education system in between  states.

Lastly, it is highly recommended to score at least 24.7, aiming towards 30.6 on their composite score in ACT exams, and at least 1167, aiming towards 1359 points on their total SAT score."# dsi25-proj1" 
"# dsi25-proj1" 
