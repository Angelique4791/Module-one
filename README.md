

#Kickstarting with Excel: Crowdfunding Analysis

##Overview of Project
Utilize raw Kickstarter data to identify trends in Kickstarter campaigns within the theater industry, with a particular focus on stage plays. This data is further broken down by launch date and the success, failure, cancelation, or live status of the campaign. This data reveals the outcomes based on their launch date. As a result of the sorting process, data regarding outcome based on goals was also discovered. This report will explain in detail how the figures in these charts were created.

###Purpose
Identify trends of success for Kickstarter campaigns in relation to launch date and goal.

##Analysis and Challenges
To find trends based on theater plays, the data first had to be sorted by category and subcategory to find theater and plays, respectively. This was done by sorting category and subcategory into separate columns. Once this was completed, the campaigns were sorted by the status of the campaign: successful, failed, live or canceled. A sheet for “Successful US Kickstarter Campaigns” and “Failed US Kickstarter Campaigns” were created to hold those respective outcome data. This had to be further sorted by the launch date. Using a timecode conversion, the column “Date Launched” was created in order to track the dates of Kickstarter campaigns examined in this report.

###Analysis of Outcomes Based on Launch Date
The data shows that May is the month with the most successful outcomes and December is the month with the least successful outcomes. Failed outcomes remain fairly consistent throughout the year, nearly equaling successful Kickstarter campaigns in December.

###Analysis of Outcomes Based on Goals
The data shows that Kickstarters with a goal of 1000 to 4999 were the most successful range of campaigns. As campaign goal increased from that range, success rate fell.

###Challenges and Difficulties Encountered
To sort data by category and subcategory, the “Category and Subcategory” column was sorted into separate columns. By filtering the outcome column, the sheets “Successful US Kickstarters” and “Failed US Kickstarters” were created. In order to compare successful and failed Kickstarter campaigns by date, another column was created to convert the “launched at” column and the “deadline” column from Unix timecode to calendar date.

##Results
The data suggests that Kickstarter campaigns launched in May are most likely to succeed while campaigns started in December are most likely to fail. Analyzing the outcome based on goal reveals the highest success rate is Kickstarters with a goal between $1000 and $4999. The likelihood of success falls as goal increases and the data may be skewed by some of the higher goals.

