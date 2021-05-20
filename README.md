# kickstarter-analysis
Data Analytics Boot Camp M1 Challenge
# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project is to analyze the succession of each campaign based on their found-rising goals. Using PivotTable, we analyzed each outcome based on campaign category and year of the campaign. In addition, we conducted basic percentage analysis of outcome based on the campaign goals. Lastly, the project visualized the analysis to aid the further analysis.



## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Utilizing PivotTable function of excel, I set outcome as column and values with campaign month as rows. I set category and year of campaign as filters. This arrangement allows me to analyze the effect of launch date on the outcome of a campaign. I then visualized the outcome, with respect to theatre category, based on the launch date. On the x-axis, there is the month, and the number of causes with respect to each outcome is on the y-axis.

### Analysis of Outcomes Based on Goals

In a new worksheet, I crested a ranges of goal to analyzed the outcomes of campaigns. Using conditional counting function of the excel (`COUNTIFS()` function), I counted number of successful, failed and canceled campaign and calculated the percentage of each outcome. I visualized the findings by plotting goal range on the x-axis, and percentage on the y-axis.

### Challenges and Difficulties Encountered

The possible challenge to this analysis could be caused by the fact that the campaigned occurred in different country with different category of campaign. Each category could exhibit very different market behaviour caused by foreseeable seasonal demand fluctuation, which can threaten the both descriptive and normative function of our analysis. The way to overcame this challenge, at least for the normative function of our analysis, is to build a probit regression to predict the success of each campaign.



## Results

Over the years, the yearly total number of campaign peaked at May, and the number of campaign decreases until the end of the year. With an exception of December, the successful campaigns outnumbers failed campaigns. The number of canceled campaign stayed at a same level throughout the year.

In particular, theatre campaign peaked in May too. The declining trend in the rest of the year is same as the overall trend, with an exception in October where number of campaign shows a transient increase. Unlike the overall campaign, the theatre campaigns' failed cases does not successful cases in any given month.

Overall, the percentage of failed campaign exhibits an increase with found-rising goals; on the other hand, the percentage of successful campaign exhibits a decreasing trend. Percentage of successful campaign is above that of the failed one for most of the goal range with an exception of the goal range from \$25,000 to \$39,999 and above \$50,000. The most successful goals are either somewhere below \$24,999 or in the range of \$40,000 to \$49,999. Percentage of canceled campaigned stay stable with exception for campaign goal greater than \$50,000 and for the goal ranging from \$5,000 to \$9,999.

The limitation of dataset is that it does not provide a more detailed information on backers of each campaign. This information would give us a more detailed and micro understanding of the operation of each campaign. That being said, this can be tackled by adding an average donation of each backer in each campaign. This way we would get more information on backers' motivation level and the expectation information. This average information combined with percentage founded information, we would get an insightful picture of each campaign.
