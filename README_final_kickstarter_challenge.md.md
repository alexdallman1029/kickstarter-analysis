# Campaign Outcomes Based On Their Launch Dates and Their Funding Goals
## Overview
### Purpose
The purpose of this analysis was to use data obtained from a popular crowdfunding website to understand the success rate of Kickstarter campaigns when examining launch dates and funding goals.
## Analysis and Challenges
Data was initially collected from a popular crowdfunding website (N = 4,115) and populated in excel for analysis. 
### Analysis of Outcomes Based on Launch Date
First, a sample was taken from the data to include a count of successful, canceled, and failed campaigns in the theater category (n = 1,369) compared to launch date by month. This was done by creating a pivot table, in which "months of year" was used for rows, and the count of successful, canceled, and failed campaigns was used for columns. A pivot chart was then created from the pivot table, filtering for "years" and by "theater." See Figure 1 below. The total number of successful campaigns was 839, canceled campaigns was 37, and failed campaigns was 493. The months of May and June had the most successful campaigns, at 111 and 100, respectively. The fewest successful campaigns occurred in the months of November and December, at 54 and 37, respectively. May, July, and October had the most failed campaigns at 50, 50, and 52, resepctively. The month with the most canceled campaigns was January, at 7.

### Challenges of Outcomes Based on Launch Date
The challenge of not providing a more robsut understanding of the data arises in the analysis, as this picture of the data does not answer the question of how much more successful the indicated months were. The month of May had both the most successful and the most failed campaigns, which may be misleading if only one of those data points is used without reference to the other. Further more-robust analysis would be needed to answer this question. 

<br><b>Figure 1</b><br><br>
<img src="resources/Theater_Outcomes_vs_Launch.png" width=1000><br>
### Analysis of Outcomes Based on Goals
To analyze the Kickstarter outcomes based on goals, a table was created with the goal amount in $5,000 increments in rows (< $1,000, $1,000-$4,999, $5,000-$9,999, $10,000-$14,999, $15,000-$19,999, $20,000-$24,999, $25,000-$29,999, $30,000-$34,999, $35,000-$39,999, $40,000-$44,999, $45,000-$49,999, and > $50,000). For each goal increment, the number of successful, canceled, and failed campaigns; the total number of campaigns; and the percentage of successful, canceled, and failed campaigns was calculated using the "COUNTSIF()" function in excel. Total number of campaigns for each category are below, in Table 1.

<br>Table 1<br><br>![image](https://user-images.githubusercontent.com/10467547/146454417-dfe98aff-495b-4046-ae00-e4e0328c0797.png)<br><br>

A line chart was then created to visualize the percentage of successful, canceled, and failed campaigns by goal increment. The highest percentage of successful campaigns (76%) were those with goals of less than $1,000. The lowest percentage of successful campaigns (0%) were those with goals between $45,000 and $49,999. See Figure 2.

### Challenges of Outcomes Based on Goals
The challege of not providing more robust data was also prevalent in this analysis. The data could be misleading if only Figure 2 was provided, as it does not account for how many successful and failed campaigns were in each goal increment, only the percentage of success and failure within those increments. Futher analysis would be needed to account for number of total campaigns in each goal range. Another challenge includes not making the data specific to the theater category.
<br><br><b>Figure 2</b><br><br>
<img src="resources/Outcomes_vs_Goals.png" width=1000><br><br>
## Results
### Theater Outcomes by Launch Date
The months of May or June will most likely provide a higher chance of success for a Kickstarter campaign in the theater category. November and December will most likely provide a lower chance of success for a Kickstarter campaign in the theater category. More Kickstarters, regardless of if they succeed or fail, take place in May, and fewer take place in the months of November, December, and January, possibly due to the proximity to the holiday season and financial end of year. Further analysis would be needed to confirm that. 

### Outcomes Based On Goals
Goal amount may also play a part in Kickstarter campaign success, but the analysis shows there is not a consistent trend upward or downward in regard to goal increments. Correcting for lower sample size in the higher goal increments might show a more consistent downward trend, in which lower goal amounts tend to be more successful. 

### Limitations 
Limitations include needing to further analyze the data for more robust measures, as stated above in the section regarding challenges, in order to get a clearer picture on how much goal amount and launch date affect the success of a Kickstarter campaign. Using more descriptive statistics could provide this type of analysis.

### Future Research 
Creating a Outcomes Based on Goals chart specifc to the theater category would provide a more relevant perspective, and providing an Outcomes by Launch Date for days of the month instead of months could also show useful trends.  
