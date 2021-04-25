# Kickstarting with Excel

## Overview of Project
This project analyzed Kickstarter fundraising campaigns occurring between the years 2009 and 2017 in the plays subcategory to understand success and failure in meeting campaign goals relative to launch dates and funding goals.

### Purpose
Louise's fundraising campaign came close to it's goal. The purpose of this analysis is to help Louise understand the performance of similar Kickstarter campaigns. This knowledge could help improve her chances of reaching her goal should she wish to launch another campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The chart Theatre_Outcomes_vs_Launch.png shows the number of successes, failures and canceled campaigns, globally in the Theatre category. 

![Outcomes_Based_on_Launch_Date](resources/Outcomes_vs_Goals.png) shows the number of successful, failed and canceled campaigns by the month in which the campaign was launched. Campaigns launched in May through July showed a greater rate of success than other months of the year. The month of December was a particularly poor month for campaign success. 

It should be noted the dataset included no data on failures and cancellations for the years 2009 - 2013. The 100% success rate in these years can bias the results. Filtering out these years, however did not alter the general trends. **Insert new line graph with years 2014-2017**

Line graphs make judging the total number of campaigns and the rate of success by month difficult. A stacked bar chart **insert chart** shows the months of May through July had the greatest number of campaigns. The number of campaigns launched was lowest in December. 

A 100% stacked bar chart allows us to see the percentage of successes, failures and cancels by month.  **insert 100% stacked bar chart** This chart shows the success rate may not vary as dramatically across months as the line graphs may suggest.  

Conclusions: 
1) More campaigns are launched in the months May thru July; competition for donors will be highest
2) Campaigns launched in May and June had the highest success rates and campaigns launched in December had the lowest success rate. Further assessment is needed to assess whether campaigns launched in the summer months tend to be more successful than those launched in other months.

### Analysis of Outcomes Based on Goals
The Chart Outcomes Based on Goals **insert chart** shows the percentage of success and failures by the campaign goal in what appears to be local currencies. Any conclusions based on this graph are meaningless due to the inconsistent currency units.

Filtering the dataset to US Kickstarter campaigns for the subcategory Plays, for the years 2014-2017 would provide a relevant dataset for Louise's question. This filters out years with biased data as well as non-US currencies. Alternatively, currencies could be converted to a common base.

The line chart Outcomes by Campaign Goal **insert chart** shows no correlation between success rate and campaign goal. It is possible there are confounding factors to be considered.

One possibility is the Staff Pick badge. It is generally accepted that projects receiving this endorsement have increased odds of success. Unfortunately the reliability of this data is suspect. **A Hack A Day** study in 2015 ["The Problem with Kickstarter: A Lack of Transparency"](https://hackaday.com/2015/08/25/the-problem-with-kickstarter-a-lack-of-transparency/) reported Kickstarter staff pick badge status is correlated with success, but how the projects were selected is mysterious. A 2016 **The Next Web** story ["Kickstarter kills 'staff picks' in favor of official badges to avoid confusion"](https://thenextweb.com/news/kickstarter-kills-staff-picks-in-favor-of-official-badges-to-avoid-confusion) reported some campaigns forged their Staff Pick status. I assume forged Staff Pick badges are not captured in the dataset, which could have impacted the success of a campaign in ways we cannot measure.

### Challenges and Difficulties Encountered
One of the difficulties in analyzing this dataset is the lack of definition for each variable. Precise definitions, along with valid values and interpretations would be very helpful and ensure the data is interpretated correctly. For example. it is unclear whether the goal and pledges data is in local currency or converted into one common currency.

Another issue is what seems to be the incomplete data for 2009-2013. Only successes are present. This raises the question of whether this is a complete dataset.

I have dealt with these issues by filtering the data to US campaigns, all assumed to be expressed in US dollars, and limited the years studied to 2014 - 2017. 

Although there is a substantial amount of data available, unavailable are many other factors that can impact the success of a campaign. For example, supplemental marketing efforts by the campaign owners, the genre of the play and the effectiveness of the play's description can be expected to play a role. A follow-on study could classify the plays subcategory campaigns on these factors.

Because this is an observational rather than experimental study, the identified relationships cannot be interpreted as causal.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
 
1) More campaigns are launched in the months May thru July; competition for donors will be highest
2) Campaigns launched in May and June had the highest success rates and campaigns launched in December had the lowest success rate. Further assessment is needed to assess whether campaigns launched in the summer months tend to be more successful than those launched in other months.

- What can you conclude about the Outcomes based on Goals?

The line chart Outcomes by Campaign Goal **insert chart** shows no correlation between success rate and campaign goal. It is possible there are confounding factors to be considered.

- What are some limitations of this dataset?

For the years 2009-2013, only successful campaigns are captured. For that reason, only the time period April 2014 - February 2017 can be used for analysis. 


- What are some other possible tables and/or graphs that we could create?

A stacked bar chart over year/month shows what appears to be a declining number of campaigns in the US Plays subcategory from 2014 to 2017. **insert chart** It would be good to learn more about the reasons behind this. Maybe play companies are finding other options more valuable than Kickstarter.

Success appears to be strictly defined as pledged >= goal. It may be useful to look at Percentage Funded as the measure of success.

