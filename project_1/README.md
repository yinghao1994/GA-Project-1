# Project 1: SAT & ACT Analysis - README.md
#### Don Chng, General Assembly SG-DSI-14
#### April 20, 2020

## Problem Statement

Currently, the only two oligopolies in the American College Admission Test industry are the College Board and ACT Inc. Within an ever increasing competitive landscape, it is of importance that the data collected on ACT and SAT partcipation rates as well as test scores, be used for analysis. Thus, this research aim to find out in which areas or states can the College Board focus their efforts on boosting participation rates.  

## Executive Summary

Through the course of this project, we executed and documented the process of obtaining text-based data, cleaning and organizing in our Python Pandas DataFrames, and plotting data to extract meaningful insights.

Data is displayed both in queried tabular form as well as in Histograms, Scatter Plots, and Box Plots from Python's Seaborn/Matplotlib visualization libraries. Through the use of these displays, assembled with custom-built functions, we identified a strong growth opportunity for the College Board in the state of New Mexico.

## Data Dictionary  
  
|                      Feature                      |   Type   | Dataset | Description                                                  |
| :-----------------------------------------------: | :------: | :-----: | :----------------------------------------------------------- |
|                     **State**                     | *object* | SAT/ACT | States in the United States of America.                   |
   | **SAT_Participation_2017, SAT_Participation_2018** | *float*  |   SAT   | SAT participation rate 
| **SAT_R&W_2017**, **SAT_R&W_2018**  | *int*  |   SAT   | Average scores by state for the SAT subject of Evidence Based Reading and Writing 
| **SAT_Math_2017**, **SAT_Math_2018**  | *int*  |   SAT   | Average scores by state for the SAT Math subject 
| **SAT_Total_2017**, **SAT_Total_2018**  | *int*  |   SAT   | Average Total scores (from 400 to 1600) by state  
| **ACT_Participation_2017, ACT_Participation_2018** | *float*  |   ACT   | ACT participation rate 
| **ACT_English_2017**, **ACT_English_2018**  | *float*  |   ACT   | Average scores by state for the ACT English subject 
| **ACT_Math_2017**, **ACT_Math_2018**  | *float*  |   ACT   | Average scores by state for the ACT Math subject 
| **ACT_Reading_2017**, **ACT_Reading_2018**  | *float*  |   ACT   | Average scores by state for ACT the Reading subject 
| **ACT_Science_2017**, **ACT_Science_2018**  | *float*  |   ACT   | Average scores by state for the ACT Science subject 
| **ACT_Composite_2017**, **ACT_Composite_2018**  | *float*  |   ACT   | Average ACT Composite scores (from 1 to 36) by state 


## Conclusions & Recommendations

### Key takeaways and Recommendations
  
    
      
**Impact of State Legislations on ACT/SAT Participation Rates**  
  
Based upon observation of the data and preliminary findings, we see that the State Law and the State's Education Board play a pivotal role in participation rates of these college tests. Winning the bid to administer these college tests to high schools would certainly see a shift in participation rates for one test over the other. Furthermore, the majority of States mandate that sitting for a college readiness test is compulsory. In statistical terms, participation rates for both ACT and SAT in these states are more likely to exceed 100%, because ACT and SAT are oligopolies over other test administrators. However, there are a few states, such as Alaska, which do not mandate compulsory college tests. In those states, both ACT and SAT participation rates added together would be much lower.  

**Recommendation: Focus efforts onto Alaska**

The College Board can consider focusing their efforts onto Alaska to boost Participation Rates. With the expiration of the State Law that mandates compulsory College Readiness Tests, ACT Participation Rates have nosedived and SAT Participation Rates have increase by a slight margin. With the reduced legislation resulting in less barriers to entry for the College Board against ACT. This would be a prime opportunity the College Board to gain an edge over ACT by increasing their market share. 


*Strategy*  
  
- Marketing efforts can be focused onto Alaska to increase participation rates. With no mandatory college examination in place for Alaska, there are new potential customers left untapped that can be reached out to. 
- Continue to communicate with the State's Education Board and keep an eye out for any opportunities to rebid if the Alaskan State chooses to renew the expired legislation. 
- The College Board can consider giving subsidized or free tests in Alaska, so as to garner more interest for students who are not well versed with the SAT. 

