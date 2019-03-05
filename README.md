
 
# README 

# Project 1: Standardized Testing, Statistical Summaries and Inference


# A Texas Size Opportunity for the College Board


# Christopher Williams 

### Information delivered 

This project consists of the following data: 

Github repository at: https://github.com/cdubbs512/SAT_or_ACT_in_Texas

Github repository includes:
 
- Jupyter notebook of python code
- PDF of presentation
- Data
- Code
- Assets (pictures etc.)
- README - Final Project 1 - Christopher


### Provided Guidance on Project (provided by General Assembly for Data Science Immersive) 

For our first project, we're going to take a look at aggregate SAT and ACT scores and participation rates from each state in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states.

Generally speaking, you will be asked to come up with a data science problem. Here's a specific prompt that should help you craft this statement:
> The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. Your presentation and report should be geared toward **non-technical** executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in a **state of your choice**.

I decided to look at **Texas**, where I live, in light of the currently being discussed proposal to mandate either the SAT or ACT for High School students.

The data we were provided with composed of the average scores of each tests’ sections and the overall composite scores. I cleaned it accordingly, conducted exploratory data analysis on it, used Tableau to visualize the data, and analyzed the data using descriptive and inferential statistics.

My presentation is as follows and the link to the project can be found here on GitHub.

# Introduction - A Texas Size Opportunity for the College Board


### Introduction on Texas focus of SAT & ACT Data
Texas is the second largest market of SAT test with 226,374 students taking the SAT in 2018 out of the 341,613 High School Graduates or 66% of 2018 class.

In 2018 Texas represents 10.5% of all 2018 US SAT test takers.

As of August 2018, Texas education policy makers at Texas Education Agency have proposed a decision to require the SAT or ACT for high school students as part of their Federally Mandated testing.

“In a proposed change to its administrative rules, the TEA said it would use the ACT and SAT — two standardized tests administered for college admissions — to test those students in high school, and that school districts and charter schools should pay for them.” - Texas Tribune

“Specifically, the proposed amendment would modify subsection (e) to require school districts to use the SAT or ACT to fulfill federal high school assessment requirements for students who took the State of Texas Assessments of Academic Readiness (STAAR®) Algebra I EOC assessment or both the STAAR® English I and English II EOC assessments prior to high school. “
	
Texas Education Agency (August 24, 2018)


### Problem Statement

In light of the above proposal, how can we use the data provided to help the College Board expand the SAT in the Texas market and not lose the foothold it has to the ACT. 

#### Further Insight on Problem Statement

This potential change to Texas High School educational testing requirements could be good or bad for the College Board and SAT testing participation in Texas.

The problem is that the College Board could be on the losing side of this proposal if the Texas Legislature and school administrations deem the ACT to be a better exam for their testing needs. The SAT could lose its share of students it currently test.

The data science problem the College Board needs to solve is to empirically prove the SAT is a better test than the ACT for the needs of the Texas Education Agency's federally mandated assessment requirements. 

The optimal result would be to gain the rest of the Texas student population. 

The information we were provided (discussed above in Overview) is not sufficient to draw conclusions on the problem of empirically proving that the SAT is a better choice than the ACT for measuring student's preparation to fulfill the federally mandated assessments. 

As policy makers often make decisions based on average testing score results, we must avoid the pitfalls of policy makers potentially misunderstanding inverse relationship between testing participation and mean scores.

For more of presentation, see pdf titled: Project1 CW SAT, ACT 2017 and 2018 - Focus on Texas - FINAL Presentation




### Overview of Data

Data utilized in this project to analyze SAT and ACT participation and scores was from 2017 and 2018 graduating classes and consists of the following data for the 50 US states and DC:


|Column Name|Type|Dataset|Description|
|---|---|---|---|
|state|object|Both|The state data consists of the 50 US states and DC| 
|participation_sat17|float|SAT|The SAT exam participation rate of state's seniors | 
|erw_sat17|int|SAT|ERW is Evidence-Based Reading and Writing average score. Possible range is 200 to 800 | 
|math_sat17|int|SAT| Average Math section score from possible 200 to 800| 
|total_sat17|int|SAT|The Total SAT score averages from possible low of 400 to maximum of 1600| 
|participation_sat18|float|SAT|The SAT exam participation rate of state's seniors | 
|erw_sat18|int|SAT|ERW is Evidence-Based Reading and Writing average score. Possible range is 200 to 800 | 
|math_sat18|int|SAT| Average Math section score from possible 200 to 800| 
|total_sat18|int|SAT|The Total SAT score averages from possible low of 400 to maximum of 1600| 
|participation_act17|float|ACT|The ACT Participation rate per state's seniors| 
|english_act17|float|ACT|The ACT English score ranges from possible low of 1 to maximum of 36| 
|math_act17|float|ACT|The ACT Math score ranges from possible low of 1 to maximum of 36| 
|reading_act17|float|ACT|The ACT Reading score ranges from possible low of 1 to maximum of 36| 
|science_act17|float|ACT|The ACT Science score ranges from possible low of 1 to maximum of 36| 
|composite_act17|float|ACT|The Composite ACT score consists of the averages of the test sections and ranges from possible low of 1 to maximum of 36| 
|participation_act18|float|ACT|The ACT Participation rate per state's seniors| 
|composite_act18|float|ACT|The Composite ACT score consists of the averages of the test sections and ranges from possible low of 1 to maximum of 36| 


Some of the data was provided as discussed below in Provided Data. Other the 2018 SAT and ACT data was collected by the students participation in the project. 

The purpose of the project was to take the raw SAT and ACT data clean it, modify it, analyze it and visualize it to gain insight of the whole and for use in a presentation on a particular state, in my case I choose Texas.

Find the conclusions on my presentation in the included in the github repository. The presentation is the pdf titled: Project1 CW SAT, ACT 2017 and 2018 - Focus on Texas - FINAL Presentation


### Provided Data

For this project, we were provided the following two provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). 


#### Additional Data and Sources 

- 2018 state-by-state average results and participation for the SAT are available in PDF reports [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 
- 2018 ACT state-by-state mean composite scores and  participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .
- SAT Results - Class of 2018 (https://reports.collegeboard.org/sat-suite-program-results/class-2018-results) 
- CollegeBoard 2018 SAT Suite of Assessments Annual Report Texas (https://reports.collegeboard.org/pdf/2018-texas-sat-suite-assessments-annual-report.pdf)
- Here are the Average SAT Scores by State (https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)
- How the New SAT Is Scored (https://blog.collegevine.com/how-the-new-sat-is-scored/)
- How Is the ACT Scored? (https://blog.prepscholar.com/how-is-the-act-scored)
- All Average ACT Scores by State (2017) (https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)
- SAT Texas (https://reports.collegeboard.org/pdf/2017-texas-sat-suite-assessments-annual-report.pdf)
- SAT California (https://reports.collegeboard.org/pdf/2018-california-sat-suite-assessments-annual-report.pdf) 
- Which States Require Students to Take the SAT or ACT? (An Interactive Breakdown of States’ 2016-17 Testing Plans)(https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html)
- Texas wants schools to pay for ACT and SAT exams. Local districts say that’s unreasonable. (https://www.texastribune.org/2018/10/03/standardized-testing-ACT-SAT-pay-Texas/)
- 18_08 Proposed Amendment to 19 TAC §101.3011 (https://tea.texas.gov/About_TEA/Laws_and_Rules/Commissioner_Rules_(TAC)/Proposed/18_08_Proposed_Amendment_to_19_TAC_%C2%A7101_3011/)

