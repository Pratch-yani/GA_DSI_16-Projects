# Project 1: SAT & ACT Analysis


## Problem Statement
Participation rates on the SAT test has been overtaken by ACT since 2012.  College Board released the new format in March 2016, and would like to identify priority state(s) to focus the efforts and resources in driving SAT participation rates going forward.  


## Executive Summary

**Objective:** To increase SAT participation rates, by identifying state(s) that College Board can focus its efforts and resources.

**Process:** 
To address our problem statement, the following approach was taken:

- Compiling data from SAT and ACT from 2017 and 2018
  - Import, Cleaning and Editing
- Exploratory Data Analysis and Data Visualizations
  - Translating data into visualizations charts to observe patterns 
  - Understanding patterns, anomalies on the charts
- Outside Research to support findings & recommendation

**Outcome:** 
Provide College Board with recommendations on which state(s) to focus on in order to drive SAT participation rates going forward.


## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*string*|SAT/ACT|US States (50 States + District of Columbia).| 
|**sat17_participation**|*float*|SAT|The percent participation on SAT test (class of 2017).|
|**sat17_erw**|*integer*|SAT|The average Evidence-Based Reading and Writing (ERW) scores (400-800) for SAT 2017.|
|**sat17_math**|*integer*|SAT|The average Math scores (400-800) for SAT 2017.|
|**sat17_total**|*integer*|SAT|The average Total scores (800-1600) for SAT 2017.|
|**act17_participation**|*float*|ACT|The percent participation on ACT test (class of 2017).|
|**act17_english**|*float*|ACT|The average Engligh scores (1-36) for ACT 2017.|
|**act17_math**|*float*|ACT|The average Math scores (1-36) for ACT 2017.|
|**act17_reading**|*float*|ACT|The average Reading scores (1-36) for ACT 2017.|
|**act17_science**|*float*|ACT|The average Science scores (1-36) for ACT 2017.|
|**act17_composite**|*float*|ACT|The average Composite scores (1-36) for ACT 2017.|
|**sat18_participation**|*float*|SAT|The percent participation on SAT test (class of 2018).|
|**sat18_erw**|*integer*|SAT|The average Evidence-Based Reading and Writing (ERW) scores (400-800) for SAT 2018.|
|**sat18_math**|*integer*|SAT|The average Math scores (400-800) for SAT 2018.|
|**sat18_total**|*integer*|SAT|The average Total scores (800-1600) for SAT 2018.|
|**act18_participation**|*float*|ACT|The percent participation on ACT test (class of 2018).|
|**act18_english**|*float*|ACT|The average Engligh scores (1-36) for ACT 2018.|
|**act18_math**|*float*|ACT|The average Math scores (1-36) for ACT 2018.|
|**act18_reading**|*float*|ACT|The average Reading scores (1-36) for ACT 2018.|
|**act18_science**|*float*|ACT|The average Science scores (1-36) for ACT 2018.|
|**act18_composite**|*float*|ACT|The average Composite scores (1-36) for ACT 2018.|






## Conclusions:

From the EDA, Visualizations, and outside research, **there are 3 states of interest** for College Board to increase SAT participations.  These are states that ranked lowest in SAT participation rates (red bars on the top), while they are not mandatory states for ACT (blue bars not = 100% participation). 

- Iowa
- Kansas
- South Dakota

![Image of State Participations](https://github.com/Pratch-yani/dsiprojects/blob/master/Project1234/project_1/plots/participation_by_state.png)

**Out of the 3 states of interest, IOWA has the highest potential.**

- **Highest population among the 3 states.**  Gaining state participation in Iowa (3.96 Million Population) will have higher impact on the National average particiation.  Second priority is Kansas (2.9 Million), while South Dakota is as smaller opportunity (884 Thousand).

- **Opportunity to replace the current state assessment tests.**. 
  - All 3 states are using non SAT/ACT for high school tests, providing an opportunity for SAT.  For students looking to apply for college, switching to SAT will take the burden of their time to prepare for college admissions, while also encouraging those who may not consider apply for college to do so given less barrier on time and resources (as seen in the case of Illinois).
  - Greater opportunity for Iowa and Kansas as they are currently using local tests (Iowa State-wide Assessment - ISASP) and Kansas Assessment Program - KAP, while South Dakota is currently using Smarter Balanced, a standardized high school test used in many states, i.e. California, Connecticut).
  - Source: https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html
  
- **Additional research show supporting information for Iowa.**
  - **Relatively stronger financials vs. Kansas:** With higher tax revenue (USD 9.5 vs. 8 Billion), higher federal aid (USD 6 vs. 3.9 Billion), and relatively lower debt USD 6.12 Billion in fiscal year 2015 (ranked 37th among the states in debt).  (Source: https://ballotpedia.org/Iowa_state_budget_and_finances)
  - **Focus on education:** Education accounted for 41.6 percent of state expenditures in fiscal year 2015.
  - **Need for change with support from legislators:**
    - Based on the article Money is the key to education in Iowa, there is a sentiment around need for a change for Iowa regarding measures of education success for students, while the main constraint is money.  Iowa is ranked 25th in per-pupil spending (USD 13,531 vs. USD 14,273 National Average).  Fortunately, some advocates and legislators continue to push for higher funding.  Last session, the Iowa Legislature also increased funding by 2.1%.
    - A few quotes that implies "need for change":
      - "Iowa has lost its leadership position in national rankings," 
      - In recent years, some of the stats that have come to define educational success have changed, and not always for the better. Sometimes those numbers haven't changed, but other states have made gains that Iowa students aren't necessarily seeing. 
      - Source: Article: Money is the key to education in Iowa https://qctimes.com/news/local/education/the-numbers-money-is-the-key-to-education-in-iowa/article_1d1578dc-0050-5814-91f7-ef3a74da739d.html

  

**Prioritized list of states with high opportunity to target**


|Priority|State|2018 SAT Participation|Population|Current High School Test|
|---|---|---|---|---|
|1|**Iowa**|3%|3,962,077|Iowa State-wide Assessment(ISASP)|
|2|**Kansas**|4%|2,913,314|Kansas Assessment Program. (KAP)|
|3|**South Dakota**|3%|884,659|Smarter Balanced (standardized test)|

Sources: (State Population)
https://en.wikipedia.org/wiki/List_of_states_and_territories_of_the_United_States_by_population


## Recommendations:

**Adopt same strategy as for Colorado & Illinois with State Contracts (SAT School Day Program), focusing on Iowa, followed by Kansas.**  This may require changes in legislation for the particular state to allow competitive bidding.  
  
**Key message to convince legislators & Department of Education:**
  - Redirecting the funds spent on local high school tests to state-funded SAT will release the state's resources to on other matters, while ensuring that student's measurement of academic success is achieved and competitive with other states nationwide.
  - For parents and students, this will benefit students who are applying for college by putting less time and burden on preparing for standardized tests, while also benefiting those who previously were not planning to apply for college by increasing their readiness and affordability as the test will be state-funded.
  


















