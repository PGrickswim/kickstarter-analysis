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

*Challenges*

Working with a very large dataset presented a few challenges that needed to be overcome. It was important to filter data that was not needed, but also to understand which columns were being filtered and ensuring that the filters weren't cloaking important data from being viewed. For example, if at one point of the project only US campaigns were being considered and an appropriate filter was set, it would be very important to then later remove that filter before understanding global performance against fiscal goals including all nations. Also, a challenge that was encountered involved pivoting dates. It is important to group or ungroup the dates as appropriate to ensure that the correct date format is displayed in the pivot table. Also, when months needed to be showing, the "Years" and "Quarters" options that appeared as default both had to be removed.
     
All in all, despite the challenges, the analysis was able to be completed in a satisfactory manner, and inferences about the results appear below.

### Analysis of Outcomes Based on Launch Date

See below for outcomes based on the month of launch for theater campaigns. While the number of failed campaigns is relatively constant throughout the year, the number of successful campaigns clearly peaks in the spring months of May and June. There is a secondary peak in February where almost twice as many campaigns are successful than those that fail. The data points to December as the month when most campaigns fail.

![Theater](https://raw.githubusercontent.com/PGrickswim/kickstarter-analysis/main/Theater_Outcomes_vs_Launch.png)
---

[Theater Outcomes](https://raw.githubusercontent.com/PGrickswim/kickstarter-analysis/main/Theater_Outcomes_vs_Launch.png)

### Challenges and Difficulties Encountered

## Results

### Analysis of Outcomes Based on Goals

![2021 12 13-Outcomes-Based-On-Launch-Date-Image](https://user-images.githubusercontent.com/95391827/146113331-ed3cde3a-fea4-4619-98ad-272434b28b09.png)
---

[Launch Date Chart](https://user-images.githubusercontent.com/95391827/146113331-ed3cde3a-fea4-4619-98ad-272434b28b09.png)

---

### Analysis of Outcomes Based on Goals

You also may be interested in outcomes based on the category of campaign. I've included that below as well, again with a link to the file underneath.
![2021 12 13-Parent-Category-Outcomes-Image](https://user-images.githubusercontent.com/95391827/146113519-369e60ed-9242-4b2e-a1a4-e60a84607cc6.png)
---
[Category Outcomes](https://user-images.githubusercontent.com/95391827/146113519-369e60ed-9242-4b2e-a1a4-e60a84607cc6.png)

The dataset used does have limitations. First, the data within it is only as accurate as we accept it to be. If the data was collected or built in a faulty way, some of the variables and values represented therein may be incorrect. We have no way of knowing this, so we must accept the data at face value for the most part. There is the ability to conduct statistical analysist to find outliers, but understanding whether they are typographical errors that need to be removed, or a campaign with a $1,000,000 goal that just really *swung for the fences* is up to the interpretation of the analys. Also, the completeness of the dataset is limited to that which could be collected. There may be other relevant datapoints that were not included. Finally, there will always be variables that influence human behavior that go beyond what can be tracked through data.

Analysis could also be completed on outcomes by category. Theater, Music, and Film campaigns clearly have a higher degree of success (yellow portion of the column graphs) than some of the other, less used campaigns. Engaging with an audience tends to give them an experience that promotes support. These are highly preferred over other forms of fundraising. Meanwhile, observe that campaigns centered around food and games have high failure rates. These categories, while they may appeal to some, do not tend to be as successful when it comes to launching fundraising campaigns. Again, the best bet is to start by focusing on a topic related directly to performing arts.

![2021 12 13-Parent-Category-Outcomes-Image](https://user-images.githubusercontent.com/95391827/146113519-369e60ed-9242-4b2e-a1a4-e60a84607cc6.png)
---

[Category Outcomes](https://user-images.githubusercontent.com/95391827/146113519-369e60ed-9242-4b2e-a1a4-e60a84607cc6.png)
