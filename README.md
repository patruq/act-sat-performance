# SAT & ACT: An analysis on performance and participation.

### The Problem: Do States with higher overall participation rates have better SAT and/or ACT outcomes?

-------------------------------------------------

***Executive Summary***

Contents:

- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

-------------------------------------------------
### <b>SAT Data Dictionary</b>:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|The state in which the test has been taken|
|participation|float|SAT|The percentage of students haven taken the SAT (Ex: 60.0 = 60%)|
|reading_writing|int|SAT|The average score earned in evident-based reading & writing by state|
|math|int|SAT|The average score earned by students in math by state|
|total|int|SAT|Total earned score across both reading_writing and math by state|

### <b>ACT Data Dictionary</b>*

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT|The state in which the test has been taken|
|participation|float|ACT|The percentage of students haven taken the ACT (Ex 75.0 = 75%)|
|english|float|ACT|Average score earned in English subtest by state|
|math|float|ACT|Average score earned in Math subtest by state|
|reading|float|ACT|Average score earned in Reading subtest by state|
|science|float|ACT|Average score earned in Science subtest by state
|composite|float|ACT|Average score across English, Math, Reading, and Science by state|

*<i>Please Note: The 2018 ACT dataset contains only the state, participation, and composite columns</i>

-------------------------------------------------
### ***Conclusions***

- Participation has a strong, negative correlation to Total scores on SAT tests.
- One of the best examples of participation is Connecticut. With 100% participation year over year 2017-2018, this state has policies in place mandated students to take the SAT. Connecticut under performs in relation to the mean Total score in both years observed.

### ***Suggestions***

- Connecticut, a state with 100% year over year participation, has moved forward with policies replacing state-issued standardized tests for the SAT. More policies like these will lead to higher participation, but students need to be prepared before taking the exam.


### ***Additional Info Desired***

- In under standing the impact of state-wide participation on test outcomes, it would be useful to see participation data for the PSAT (or PreACT for ACT). Looking at participation in test-prep could shed more light on the effects of participation to score outcomes.

- What %'s of graduating high-school students that have taken the SAT or ACT have been accepted into 4 year universities? What about ones that have not? Data on whether students are in a position where the SAT or ACT is necessary for admissions could effect overall participation.
