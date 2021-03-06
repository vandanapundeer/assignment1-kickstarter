# Crowdfunding Analysis
## Overview of Project
In this project our goal is to provide insights to Louise about how different campaigns fared in relation to their launch dates and their funding goals. We are using excel visualization techniques to provide a summary of outcomes of theater campaigns and the factors that influence it.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
To start with the analysis we created a pivot table through which we were able to summarize the outcome of each theater campaign based on their respective launch dates. Although the pivot table contains all the required information, in order to provide a visual summary, we created a line chart using the same data which highlights the relation between different campaign outcomes with their launch date.
![Theater_Outcomes_vs_Launch](https://github.com/vandanapundeer/assignment1-kickstarter/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
Further, to see how campaigns performed in relation to their funding goals, we created 12 buckets for funding goals. This helped us divide each campaign into a different bucket based on its goal. Then for each of these buckets we calculated the percentage of successful, failed and cancelled campaigns. 
![Outcomes_vs_Goals](https://github.com/vandanapundeer/assignment1-kickstarter/blob/main/Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties
Possible challenges one could encounter would be in relation to the calcaluting the number of successful/failed/cancelled campaigns based on the buckets created for funding goals.
## Results
- The analysis shows that majority of the campaigns launched in May have been successful. This implies that May can be considered as the best month for launch of theater campaigns. 
- We can also see that the ouctomes of campaigns launched in first half of the year are relatively better as compared to those launched in the second half. So, the launch date should be avoided to be in the second half of the year.
- Campaigns with goals greater $45000 have the worst success rate as compared to others.
- There are certain campaigns in the dataset for which goal is a small number such $1. This shows that we might have unclean data.
- To help make a better decision about launch of campaigns, we could also analyze the outcomes of different campaigns based on country.
