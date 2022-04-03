# PyCity School District Analysis
## Overview
The purpose of this project was to perform an analysis, using school and student data, to inform the school district on their performance, trends, and patterns of standardized testing scores.  This will assist the school board in making decisions regarding the school budgets and priorities.  While compiling the data, I was informed that there was academic dishonesty with the Thomas High School's 9th grade testing scores.  Therefore, the Thomas High School's 9th grade math and reading scores were replaced with "NaN's".  
## Results
Replacing the Thomas High School's 9th grade math and reading scores affected 461 students.  That may seem like a significant number, but the entire student population for the school district's high schoolers is 39,170.  The Thomas High School 9th Graders account for 0.01% of the school district student population.  
### School District Summary
* Origianl School District Summary
<img width="964" alt="Original_School_District_Summary" src="https://user-images.githubusercontent.com/99417460/161442117-c8cabedb-936b-4bca-adbb-795e1f238583.png">

* New School District Summary<img width="960" alt="New_School_District Summary" src="https://user-images.githubusercontent.com/99417460/161442204-1aa75404-c03e-4508-8d62-29a6bcc681ce.png">
When assessing the average scores for the 15 schools in the school district, removing the Thomas High School 9th grade testing scores did not have a drastic affect on the overall passing scores and percentages.  The average math score dropped 0.1 point, while the average reading score remained unchanged.  The percentage of those passing math and reading dropped by 0.2% and 0.3%, respectively.  The overall passing percentage dropped 0.1%.
### School Summary
* Original School Summary
<img width="1073" alt="Original School Summary" src="https://user-images.githubusercontent.com/99417460/161442743-0f2f6dd2-a9e0-4211-8619-92f1e5673baf.png">

* New School Summary
<img width="1076" alt="New School Summary" src="https://user-images.githubusercontent.com/99417460/161442803-962ee3e0-393d-4483-93b4-8b16b545b3e7.png">
As one can see, the average math and reading score did not change much for Thomas High School when taking out the 9th Graders' grades.  However, the percentage passing math and reading changed from 93.3% & 97.3% to 66.9% & 69.7%, respectively.  The overall passing percentage changed from 90.9% to 65.0%.

* Removed 9th Graders from School Summary
<img width="1072" alt="Removed 9th Grade Scores School Summary" src="https://user-images.githubusercontent.com/99417460/161443227-19ee350a-a12c-4861-a548-7e1f9528ce58.png">
Once I removed the 9th Grade scores and percentages from the Thomas High School Summary, Thomas High School became the second best school in the district concerning overall passing percentage.

### Thomas High School's Performance Compared to Other Schools
When replacing the 9th Grade math and reading scores at Thomas High School, Thomas High School ranked 8th in the school district regarding overall passing percentage; this is the directly middle school in the district.  When removing the THS 9th Grade Scores from the equation, Thomas High School is the 2nd best performing school.
<img width="1092" alt="Top 5 performing schools" src="https://user-images.githubusercontent.com/99417460/161443624-091ab773-2eed-4b31-a444-34a5169ff9d7.png">

### Math and Reading Scores by Grade
* Math Scores by Grade
<img width="469" alt="Math Scores by Grade" src="https://user-images.githubusercontent.com/99417460/161443748-ac0ef88b-4970-4760-bd1f-00a029f36ae6.png">

* Reading Scores by Grade
<img width="468" alt="Reading Scores by Grade" src="https://user-images.githubusercontent.com/99417460/161443797-448fd857-45f4-463b-a4c6-11e0cad8bb79.png">
As you can see from the listed tables, replacing Thomas High School's math and reading scores with "NaN" did not affect the other grade and school's scores.

### Scores by School Spending
<img width="859" alt="Spending Ranges per Student" src="https://user-images.githubusercontent.com/99417460/161444280-c466b9f5-0d4f-4384-a2a8-a6f0a25be156.png">
By removing the Thomas High School (THS) 9th Grade scores from the analysis, the only listed bin that was changed was the spending range of $631-$645 per student.  The percentages and scores were only changed by hundredths of a point.

### Scores by School Size
<img width="797" alt="Scores by School Size" src="https://user-images.githubusercontent.com/99417460/161445540-a7e2b34b-b2a8-4ec4-80e6-85580eafcd7d.png">
By removing the THS 9th Grade scores from the analysis, the medium school size (1000-1999) changed slightly.  The average math dropped by 0.01%, however, the average reading score increased by 0.01%.  The passing math percentage dropped by 0.01%.  The passing reading percentage dropped by 0.06%.  The overall passing percentage dropped by 0.07%.  

### Scores by School Type
<img width="742" alt="Scores by School Type" src="https://user-images.githubusercontent.com/99417460/161445870-10fca5eb-7c09-4f91-bae8-6fd126ea7206.png">
By removing the THS 9th Grade scores from the analysis, the charter school type was slightly affected.  Again, the scores were only minimally affected.  The average math score dropped 0.01%, while the average reading score increased by 0.01%.  The percentage passing math dropped 0.01%, while the percentage passing reading dropped by 0.03%.  The overall passing percentage dropped by 0.04%.  

Even though the charter schools averages and percentages were slightly changed, charter schools still outperformed district schools in each metric.

## Summary
In summary, the data for the standardized test scores changed slightly, but overall the changes were insignificant.
* By removing the Thomas High School 9th Grade scores from the data, THS's district ranking went from 8th place to 2nd. place.
* By replacing the THS 9th Grade scores with "NaN", Thomas High School percentage passing math went from 93% to 67%, percentage passing reading went from 97% to 70%, and the overall passing percentage went from 91% to 65%.
* For the entire district summary, by replacing the THS 9th Grade scores with "NaN", the district passing math and reading percentages dropped by 0.2% and 0.3% respectively.
* Even though the overall passing percentage dopped by 0.04% for the charter schools, charter schools outperformed district schools in each metric.
