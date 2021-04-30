# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to provide playwright Louise with the information to help her successfully launch her play "Fever". "Fever" has a current projected budget of over $10,000. She wants to have her play be crowdfunded, so the information being analysed is coming from kickstarter and will focus primarily on Kickstarter campaigns in the theater category. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

One of the factors being considered for successful theater campaigns is launch date. In order to convert the orifinal Unix date code into a readable date, this formula was applied to it: "(((L2/60)/60)/24)+DATE(1970,1,1)". Looking at the Theater_Outcomes_vs_Launch.png, we can see that the most successful time to launch a campaign is in the early summer (May and June) with earlier being better. These months have a much better ratio of success (# of successful campaigns / # of failed campaigns) [>200%] compared to other months. This means that she will be twice as likely to succeed rather than fail. The worst month to start a campaign is in December with a 106% success ratio. This means that she has basically a 50/50 chance of running a successful campaign.

![Timeline Outcomes](https://user-images.githubusercontent.com/40553064/116736753-eb7dd880-a9b5-11eb-9a0f-579cd49c2465.png)

### Analysis of Outcomes Based on Goals

Another factor considered is Goal amount. By stratifying the spectrum of goals, we can see that generally, campaigns with larger goals are more likely to fail. The more she can trim down her budget, the more likely she is to be able to successfully fund her campaign. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/40553064/116736352-61ce0b00-a9b5-11eb-8516-b1fe3b0f0900.png)

### Challenges and Difficulties Encountered

One of the possible challenges for this data set is the conversion of the date from the unix code to a readable date format. First, the analyst will need to identify the date field as a unix code. Then the analyst will need to convert the unix date code into a readable date format. If this is not done correctly, the date can be either unreadable or wrong; both of those outcomes will yield a worthless analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. The best time to launch a campaign is in May
  2. The worst time to launch a campaign is in December 

- What can you conclude about the Outcomes based on Goals?

  Louise should try to trim down her budget so that she can aim to have a goal of less than $10,000

- What are some limitations of this dataset?

  One peice of data that is not included, and is a little outside the realm of kickstarter is whether or not "successful" kickstarter campaigns are actually successful. Just because a play was funded does not mean that the playwright accurately assessed the needs of the production. Someone could low-ball the budget to have a successful campaign and then return again later to get more money.
  
- What are some other possible tables and/or graphs that we could create?

  Analysis of campaign success relative to duration could lend insight to the best length of campaigns. Analysis of staff pick or spotlight may indicate whether getting help from Kickstarter itself to promote her play would be significantly helpful. Additionally, Looking at Success as it relates to country could be helpful if you can promote kickstarter campaigns in other countries.
