# School District Analysis
## Overview
For this report, student data from standardized tests and profiles of each school in the district were used to produce analyses of test scores for each school and for the district at large. Due to concerns about academic dishonesty, the analysis was then repeated with the scores for 9th grade students at Thomas High School (THS) excluded. 

The following numbers will be important throughout this report:
* **N** = 39,170 (The total number of students in the district.)
* **M** = 1,635 (The total number of students at THS.)
* **P** = 461 (The number of 9th graders at THS.)
* **n** = N - P = 38,709 (The number of total students in the district excluding THS 9th graders.)
* **m** = M - P = 1,174 (The number of students at THS excluding 9th graders.)

Except where otherwise indicated, when the number of students is N or M, the data includes THS 9th graders, and when the number of students is given as n or m, the data excludes THS 9th graders. However, total and per capita budget data is nowhere adjusted to reflect the exclusion of THS 9th graders.

## Results
### District Summary.
#### The district summary with total students = N.

![image](https://user-images.githubusercontent.com/80861610/118665135-0e82f780-b7c0-11eb-965e-33d04fc93fb8.png)

#### The district summary with total students = n.

![image](https://user-images.githubusercontent.com/80861610/118664664-a7fdd980-b7bf-11eb-9eb5-c94573a65af7.png)

* As is clear from a comparison of the district summaries, the inlcusion/exclusion of THS 9th graders has little effect of the overall district metrics. There are merely minor decreases in Average Math Score and the different Passing Percentages.

### School Summary
#### THS summary with total students = M.

![image](https://user-images.githubusercontent.com/80861610/118829674-4e171580-b88c-11eb-9308-a6963d85cddc.png)

#### THS summary with total students = m.

![image](https://user-images.githubusercontent.com/80861610/118669557-d978a400-b7c3-11eb-8e57-5e43fb8d15a0.png)

* Comparing these two summaries, we see that removing the 9th graders from the THS data results in small decreases in Average Math Score and the Passing Percentages, as well as a small increase in the Average Reading Score.

### Schools by % Overall Passing
#### School summaries ranked by % Overall Passing with THS total students = M.

![image](https://user-images.githubusercontent.com/80861610/118831563-e06be900-b88d-11eb-982c-93be5b41c011.png)

#### School summaries ranked by % Overall Passing with THS total students = m.

![image](https://user-images.githubusercontent.com/80861610/118831780-0c876a00-b88e-11eb-85f1-7899950c028e.png)

* From comparing the rankings of schools by % Overall Passing, we see that removing the THS 9th graders has no effect on the overall rankings.

### Scores by Grade
#### Math scores for all district 9th graders (total students = N).

![image](https://user-images.githubusercontent.com/80861610/118834697-65580200-b890-11eb-899b-b8d14c26da55.png)

#### Math scores for non-THS district 9th graders (total students = n).

![image](https://user-images.githubusercontent.com/80861610/118834591-52453200-b890-11eb-8461-9315275ae11d.png)

#### Reading scores for all district 9th graders (total students = N).

![image](https://user-images.githubusercontent.com/80861610/118834145-009ca780-b890-11eb-8d1e-3aa51fb1af8d.png)

#### Reading scores for non-THS district 9th graders (total students = n).

![image](https://user-images.githubusercontent.com/80861610/118834049-f11d5e80-b88f-11eb-9240-e15816baefec.png)

* We also find that removing THS 9th graders has little effect on the descriptive statistics measuring the math and reading scores of 9th graders.

### Scores by School Spending
Note: THS is in the "$630-644" category.

#### Scores by school spending for total students = N.

![image](https://user-images.githubusercontent.com/80861610/118835276-d4cdf180-b890-11eb-9eca-11ee0221e2d2.png)

#### Scores by school spending for total students = n.

![image](https://user-images.githubusercontent.com/80861610/118836893-4eb2aa80-b892-11eb-9584-a11f4af8144a.png)

* Removing THS 9th graders had little impact on the scores by school spending statistics.

### Scores by School Size 
Note: THS is in the "Medium" category with or without 9th graders counted.

#### Scores by school size for total students = N.

![image](https://user-images.githubusercontent.com/80861610/118837170-8e799200-b892-11eb-87dd-4abac9942efb.png)

#### Scores by school size for total students = n.

![image](https://user-images.githubusercontent.com/80861610/118837351-b7018c00-b892-11eb-8b8e-838cb250a6b2.png)

* Removing THS 9th graders had no impact (within the margin of rounding) on the scores by school size statistics.

### Scores by School Type
Note: THS is in the "Charter" category.

#### Scores by school type for total students = N.

![image](https://user-images.githubusercontent.com/80861610/118836535-eebc0400-b891-11eb-91bd-d370f1e78c19.png)

#### Scores by school type for total students = n.

![image](https://user-images.githubusercontent.com/80861610/118836450-d946da00-b891-11eb-9e9c-6e6843ee93b4.png)

* Removing THS 9th graders had no impact (withing the margin of rounding) on the scores by school type statistics.

## Summary
We found that removing the THS 9th graders slightly lowered the Average Math and Average Reading Scores for district 9th graders. It also resulted in slightly lower passing percentages in Math, Reading, and Overall for schools in the same per-student spending category.
