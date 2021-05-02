# Kickstarting with Excel


## Overview of Project

### Purpose

This analysis will identify trends among previous fundraising campaigns to determine success based on launch dates and goals. This information will be visualized to show the months that have proven most or least successful as well as which range of goals were most or least successful.



## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Analysis of fundraising campaigns based on launch date examines 1369 theater crowdfunding campaigns. Campaigns were categorized by successful, failed, or canceled and organized by their month of launch to identify trends in launch date and outcome. 

Outcomes Based on Launch Date:

![Alt Text](https://github.com/lyanneagger/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Analysis of outcomes based on goals compares 1047 crowdfunding campaigns for plays to identify trends in goals set in successful campaigns. The number of successful, failed, and canceled campaigns was broken down into different ranges of goals to identify which was most successful. 

Outcomes Based on Goals: 
![Alt Text](https://github.com/lyanneagger/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

The raw data presented several challenges. Firstly, the data set included crowdfunding campaigns for many different and unrelated categories so they needed to be split into categories and subcategories to remove irrelevant data. Additionally, the initial launch and deadline were in Unix timestamps and needed to be reformatted to identify the full date, month, and year.

## Results

Several conclusions can be drawn based on theater outcomes based on launch date. We can see that May and June are the most successful months to begin a campaign based on high numbers of successful campaigns. In May, 111 successful campaigns and 52 failed campaigns were launched. In June, 100 successful campaigns and 49 failed campaigns were launched. In addition, it is clear that campaigns launched in December had the lowest success rate and almost an equal number of successes and failures. 

In examining outcomes based on goals, the most successful campaigns, both in number and percentage, were started with a goal of less than $5,000. Campaigns with a goal under $1,000 were successful 76% of the time, with 141 campaigns achieving their fundraising goals. Campaigns with goals between $1,000 and $4,999 were successful 73% of the time, with 388 campaigns achieving their goals.

Some of the limitations of this dataset are the location, time frame, and sample size within each. By filtering, we can see that the US only has 671 fundraising campaigns for plays. This may change the data based on cultural or regional support for plays or local economies. In addition, by filtering to recent years, different monthly trends are reflected each year and only two months (January and February) of data are provided for 2017, which may skew the overall data if the year is incomplete.

Additional graphs could provide further insight into successful campaign trends. It could help to compare the duration of the campaign to whether it was successful or what percentage of the goal was reached. It may also be helpful to examine the duration compared to the goal to determine how long it takes to successfully reach a goal once launched.
