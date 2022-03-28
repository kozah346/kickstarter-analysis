# An Analysis of Kickstarter Campaigns
A crowdfunding analysis to visualize a project campaign.
## Overview of Project
The project was analyzed by line charts whose links are provided in this file to visualize a report on how launch dates and funding goals fared.
### Purpose
This analysis was done to help Louise, a playwright, know how different campaigns fared as far as launch dates and funding goals are concerned.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
As mentioned before, this analysis was done carefully by use of line charts. The analysis for theatre outcomes based on launch date was made by creating a pivot table first that enabled the data to be separated accordingly for easy visualization. The following link shows the line chart that was created: ![alt text](Theater_Outcomes_vs_Launch.png) 
### Analysis of Outcomes Based on Goals
 Elsewhere, to create a line chart for outcomes based on goals, a regular table of rows and columns had to be created so that the COUNTIF function is used to help get the number of successful, failed and canceled projects. Later on, mathematical formula was used to get the respective percentages. The following link shows the resulting line chart: ![alt text](Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
For the outcomes based on launch date, it was fairly easy to create as all that had to be done was creating a pivot table and after that is chosing the best way to visualize. As for the outcomes based on goals, there were two challenges faced. One, was to use the COUNTIFS function and ensure the right range, outcome and play was chosen, otherwise it would result in misrepresentation of data. To overcome this challenge, careful data entry was done and had to do totals to make sure they match the original Kickstarter data. Two, once the line graph was generated, the x-axis had numbers between 1 to 13 representing the row headers instead of the ranges which gave the line chart a different meaning that would easily confuse someone trying to make sense of the analysis. This challenge was overcome by editing the chart data range by inputing 'Outcomes Based on Goals'!$A$1:$A$13 that replaced the row headers with ranges in column A.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion observed is that the number of successful projects was more than failed projects during every single month.
Another conclusion is that a lot of projects launched in the first six months' chance of success was higher compared to the last six months. 

- What can you conclude about the Outcomes based on Goals?
It is easy to notice that the chance of success for between 0 and 19000 was higher as compared to higher figures such as 50000 or more meaning that expensive projects had a chance of failure compared to lower figures.
- What are some limitations of this dataset?
Limitations of this dataset is that it is pretty specific on a particular analysis. For example, it would be crucial to focus on the deadline as well as the launch date to see the comparison throughout the year. Also, it would be important to see the countries as far as goals are concerned to see which countries have more success so as to launch projects in such countries to ensure more success.
- What are some other possible tables and/or graphs that we could create?
The outcomes based on goals would be also visualized by a stacked column. The theater outcomes based on launch date would be visualized by a clustered column. 
