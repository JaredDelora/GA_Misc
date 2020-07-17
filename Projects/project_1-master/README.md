## Problem Statement:
**How can we increase SAT test participation in New York State?**

## Executive Summary

**An analysis of 2017, 2018 SAT and ACT data, focused on New York State.**
Even though NY State already emphasizes the SAT, only about 50% of NY students take the SAT. This analysis seeks to look at the factors in NY with the goal of increasing SAT participation in NY State.


## Data Sources

[College Vine SAT Data](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)

[Prep Scholar ACT Data](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)


### Contents:
- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations


### Dictionary defining terms for the 2017 & 2018 SAT and ACT DataFrames:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|2018 Data follows 2017 naming structure|
|sat_2017_participation|float|SAT|The SAT participation percentage in 2017 (0-100).|
|sat_2017_reading_writing|int|SAT|The average SAT writing score in 2017 (200-800).|
|sat_2017_math|int|SAT|The average SAT math score  in 2017 (200-800).|
|sat_2017_total|int|SAT|The average SAT total score in 2017 (400-1600).|
|act_2017_participation|float|ACT|The ACT participation percentage in 2017 (0-100).|
|act_2017_english|float|ACT|The average ACT english score in 2017 (1-36).|
|act_2017_math|float|ACT|The average ACT math score in 2017 (1-36).|
|act_2017_reading|float|ACT|The average ACT reading score in 2017 (1-36).|
|act_2017_science|float|ACT|The average ACT science score in 2017 (1-36).|
|act_2017_composite|float|ACT|The avererage composite ACT score in 2017 (1-36).|


### Conclusions/Recommendations:

SAT Participation rates in NY State match those of the ACT, despite the heavy focus the school systems puts on SAT preparation. One-on-one tutoring is highly effective at raising SAT scores, but due to socio-economic conditions this one-on-one test prep isn't available to everyone. Funding for one-on-one SAT test preparation for everyone would do two things:
- Increase SAT scores in NY State
- Increase interest in taking the SAT due to the additional resources available
