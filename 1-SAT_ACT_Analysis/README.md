

# Project 1: SAT & ACT Analysis  

I am going to take a look at aggregate SAT and ACT scores and participation rates from each state in the United States. I'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states.

SAT dataset contains data on average Verbal, Math, Total scores along with the percentage of students who took the test in each of 51 states in 2017.

ACT dataset contains data on average English, Math, Reading, Science, and Composite scores along with the percentage of students who took the test in each of 51 states in 2017.

**SAT 2017:**
Min Verbal score: **482**  
Min Math score:**524**  
Min Total score: **950**  
Max Verbal score: **644**  
Max Math score: **651**  
Max Total score: **1295**  

**ACT 2017:**  
Min English score: **16.3**  
Min Math score: **18.0**  
Min Reading score: **18.1**  
Min Science score: **23.2**  
Min Composite score: **17.8**  
Max English score: **25.5**  
Max Math score: **25.3**  
Max Reading score: **26.0**  
Max Science score: **24.9**  
Max Composite score: **25.5**   

### 2017 Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|object|sat2017_df|The states of U.S.A|
|**sat2017_participation**|float64|sat2017_df|Rate of students who took SAT test in 2017|
|**sat2017_verbal**|float64|sat2017_df|Average SAT evidence-based Reading & Writing score in 2017|
|**sat2017_math**|float64|sat2017_df|Average SAT Math score in 2017|
|**sat2017_total**|float64|sat2017_df|Average SAT total score in 2017|
|**state**|object|act2017_df|The states of U.S.A|
|**act2017_participation**|float64|act2017_df|Rate of students who took ACT test in 2017|
|**act2017_english**|float64|act2017_df|Average ACT English score in 2017|
|**act2017_math**|float64|act2017_df|Average ACT Math score in 2017|
|**act2017_reading**|float64|act2017_df|Average ACT Reading score in 2017|
|**act2017_science**|float64|act2017_df|Average ACT Science score in 2017|
|**act2017_composite**|float64|act2017_df|Average ACT composite score in 2017|

### 2018 Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|object|sat2018_df|The states of U.S.A|
|**sat2018_participation**|float64|sat2018_df|Rate of students who took SAT test in 2018|
|**sat2018_verbal**|float64|sat2018_df|Average SAT evidence-based Reading & Writing score in 2018|
|**sat2018_math**|float64|sat2018_df|Average SAT Math score in 2018|
|**sat2018_total**|float64|sat2018_df|Average SAT total score in 2018|
|**state**|object|act2018_df|The states of U.S.A|
|**act2018_participation**|float64|act2018_df|Rate of students who took ACT test in 2018|
|**act2018_composite**|float64|act2018_df|Average ACT composite score in 2018|

#### Participation Rate % Comparison  

**2017 SAT:**  
North Dakota, Mississippi, Iowa and other mid-west states (a.k.a Heartland) have the lowest participation rate (2%).  
District of Columbia, Michigan, Connecticut, Delaware, New Hampshire and some other east-coast states have the highest participation rate (100%).  
**2018 SAT:**  
North Dakota, Wyoming, South Dakota, Nebraska, Wisconsin and other mid-west states have the lowest participation rate (2-3%). Colorado, Connecticut, Delaware, Michigan, Idaho and some other east-coast states have the highest participation rate (100%). The participation rate of Colorado have significantly changed year-to-year from 11% to 100% when the test became mandatory for getting into college.   https://www.testive.com/colorado-sat-change-2017/  
**2017 ACT:**  
Maine, New Hampshire, Delaware, Rhode Island, Pennsylvania and other north-east states have the lowest participation rate (18%).    
Alabama, Kentucky, Utah, Wisconsin, Tennessee have the highest participation rate (100%).  
**2018 ACT:**  
Maine, Rhode Island, New Hampshire, Delaware,  Pennsylvania have the lowest participation rate (15%).  
Alabama, Kentucky, Wisconsin, Tennessee, Utah have the highest participation rate (100%). These states are consistent year-to-year.  
There is a positive correlation in participation rates between years with Colorado exception. However, there is a negative correlation in participation rates of SAT and ACT tests. Demographically, east coast is SAT-dominant while mid-west is ACT-dominant.There are also neutral states that show above 50% participation on both tests like Hawaii, Florida, South Carolina, Georgia in both years.  

#### Average Total Score Comparison  

**2017 SAT:**  
District of Columbia, Delaware, Idaho, Michigan, Maine have the lowest total score (950-1000).  
Minnesota, Wisconsin, Iowa, Missouri, Kansas have the highest total score (1260+).  
**2018 SAT:**  
District of Columbia, Delaware, West Virginia, Idaho, Utah have the lowest total score (1000).   
Minnesota, Wisconsin, North Dakota, Iowa, Kansas have the highest total score (1265+).  
**2017 ACT:**  
Nevada, Mississippi, South Carolina, Hawaii, North Carolina have the lowest composite score (18-19).   
New Hampshire, Massachusetts, Connecticut, Maine, District of Columbia have the highest composite score (24+).  
**2018 ACT:**  
Nevada, South Carolina, Mississippi, Hawaii, Alabama have the lowest composite score (18-19).  
Connecticut, Massachusetts, New Hampshire, New York, Michigan have the highest composite score.(24+).  

There is a suprising result that mid-west states are consistently most successful in SAT test both years despite their low participation rate.  
"In the Midwest, the SAT is often a back-up exam for perfectionists—the students who want to exhaust every possible option before turning in their college applications." **(Ben Taylor, Forbes, June 2014)**  

#### Interesting States  

1) Colorado: Participation rate jumped from 11% to 100% year-to year. Because the test became required for college education.  
2) Mid-west states: SAT scores are highest despite low participation rate. It looks like the choice is mostly ACT and only best students take SAT as an alternative. 
