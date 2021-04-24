# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to provide Louise with the information to help her launch her play "Fever" with a current projected budget of over $10,000. She wants to have her play be crowdfunded, so the information being analysed is coming from kickstarter, and will focus primarily on campaigns in the theatre category. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

One of the factors being considered for successful theater campaigns is launch date. In order to convert the orifinal Unix date code into a readable date, this formula was applied to it: "(((L2/60)/60)/24)+DATE(1970,1,1)". Looking at the Theater_Outcomes_vs_Launch.png, we can see that the most successful time to launch a campaign is in the early summer (May through July) with earlier being better. 

### Analysis of Outcomes Based on Goals

Another factor considered is Goal amount. By stratifying the different goals, we can see that the vast majority of kickstarter campaigns are less than $10,000. The most successful tiers are the two lowest

### Challenges and Difficulties Encountered

One of the possible challenges for this data set is the conversion of the date from the unix code to a readable date format. If this is not done correctly, the date can be either unreadable or wrong; both of those outcomes will yield a worthless analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
