# An Analysis of Kickstarter Campaigns

## Overview of Project

### Purpose
The below analysis draws conclusions about the historical success of fundraising campaigns in the performing arts. This analysis can be used to make decisions about the scope, timing, and other important factors to improve the chances of a successful campaign. While the details and execution of the campaign remain the most important variables, understanding the environment in which a campaign is launched can play an important role in determining its success or failure.

### Analysis and Challenges

*Analysis*

The analysis was conducted through execution of several steps to obtain and work with a large data set to discover trends, insights, and conclusions about kickstarter campaigns over a large frame of time. 
1. First, a dataset was obtained and dowloaded to the computer
2. Next, the dataset was filtered and a pivot table was created to find occurences that fit specific criteria
3. Then, illustrative graphs were produced to quickly display trends and other relevant information.
4. Finally, the information was compiled into this report for your review.

### Analysis of Outcomes Based on Launch Date

See below for outcomes based on the month of launch for theater campaigns. While the number of failed campaigns is relatively constant throughout the year, the number of successful campaigns clearly peaks in the spring months of May and June. There is a secondary peak in February where almost twice as many campaigns are successful than those that fail. The data points to December as the month when most campaigns fail.

![Theater](https://raw.githubusercontent.com/PGrickswim/kickstarter-analysis/main/Theater_Outcomes_vs_Launch.png)
---

[Theater Outcomes](https://raw.githubusercontent.com/PGrickswim/kickstarter-analysis/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Below is a chart of the percentage of campaigns that are successful vs. failed based on the dollar amount of their fundraising goal. Generally, as goal size grows from less than $1,000 to the $30,000 range, the percentage of successes steadily declines from 80% down to 20%. However, there is data that shows that campaigns with goals of $35,000 to $45,000 have a higher degree of success. Perhaps this is due to a large enough scale that sufficient resources are often committed to aid the campaign's success, without being so lofty that the overall goal size being too large makes the campaign suffer. For significant fundraising, a goal from $35,000 to $44,999 may be a good range from within to choose.

![Outcomes Based on Goals](https://raw.githubusercontent.com/PGrickswim/kickstarter-analysis/main/Outcomes_vs_Goals.png)
---

[Outcomes Based on Goal Value](https://raw.githubusercontent.com/PGrickswim/kickstarter-analysis/main/Outcomes_vs_Goals.png)

---

### Challenges and Difficulties Encountered

*Challenges*

Working with a very large dataset presented a few challenges that needed to be overcome. It was important to filter data that was not needed, but also to understand which columns were being filtered and ensuring that the filters weren't cloaking important data from being viewed. For example, if at one point of the project only US campaigns were being considered and an appropriate filter was set, it would be very important to then later remove that filter before understanding global performance against fiscal goals including all nations. Also, a challenge that was encountered involved pivoting dates. It is important to group or ungroup the dates as appropriate to ensure that the correct date format is displayed in the pivot table. Also, when months needed to be showing, the "Years" and "Quarters" options that appeared as default both had to be removed.
     
## Results

*Conclusions*

Conclusions of the analysis of the data are included above in the "Analysis" section. To reiterate, a launch date in the spring months of May and June appear preferable due to the success of campaigns launched during those months previously. Additionally, December is a month to steer clear of for launching. With the secondary peak occuring in February, as well as a slight lift for October launches, a fundraiser would be well served to either launch 2 months before or 2 months after the holiday month of December. 

As it relates to the outcomes based on goals, plays appear to be successful when the goal is $35,000 to $45,000, not as much as the very low budget goals, but significantly more than goals nearly below and nearly above that range. Perhaps this is due to a large enough scale that sufficient resources are often committed to aid the campaign's success, without being so lofty that the overall goal size being too large makes the campaign suffer.

*Limitations*

The dataset used does have limitations. First, the data within it is only as accurate as we accept it to be. If the data was collected or built in a faulty way, some of the variables and values represented therein may be incorrect. We have no way of knowing this, so we must accept the data at face value for the most part. There is the ability to conduct statistical analysist to find outliers, but understanding whether they are typographical errors that need to be removed, or a campaign with a $1,000,000 goal that just really *swung for the fences* is up to the interpretation of the analys. Also, the completeness of the dataset is limited to that which could be collected. There may be other relevant datapoints that were not included. Finally, there will always be variables that influence human behavior that go beyond what can be tracked through data.

*Other Possible Analyses*

Analysis could also be completed on outcomes by category. Theater, Music, and Film campaigns clearly have a higher degree of success (yellow portion of the column graphs) than some of the other, less used campaigns. Engaging with an audience tends to give them an experience that promotes support. These are highly preferred over other forms of fundraising. Meanwhile, observe that campaigns centered around food and games have high failure rates. These categories, while they may appeal to some, do not tend to be as successful when it comes to launching fundraising campaigns. Again, the best bet is to start by focusing on a topic related directly to performing arts.

![2021 12 13-Parent-Category-Outcomes-Image](https://user-images.githubusercontent.com/95391827/146113519-369e60ed-9242-4b2e-a1a4-e60a84607cc6.png)
---

[Category Outcomes](https://user-images.githubusercontent.com/95391827/146113519-369e60ed-9242-4b2e-a1a4-e60a84607cc6.png)
