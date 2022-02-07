# Excel_Analysis_Projects - Kickstarting with Excel

## Overview of Project
### Purpose
   - Louise, a client, recently conducted a fundraiser for her play "Fever". She raised most of her goal in a short amount of time and wanted to see how other campains did in comparison to her in terms of time and goal attainment. We will show the outcomes based on launch date and the outcomes based on fundrasing goals to show if Louise's efforts were successful in terms of the overal landscape. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
  - Please reffer to Theater_Outcomes_vs_Launch.png in the "Resources" folder for refference
    /sorianotyler/Excel_Analysis_Projects/Resources/Theater_Outcomes_vs_Launch.png
  - Throughout the years we see that Theater funraisers have the most success if they start in May. May fundraisers saw 111 successes, 52 fails, and 3 cancellations for a total of 166 fundraisers. Which gives May a success rate of 68.5%. The next closest would be June with 100 successes out of 153 which would yeild a success rate of 65.3%.

### Analysis of Outcomes Based on Goals
  - Please refer to Outcomes_vs_Goals.png in the "Reasources" folder for reference
    /sorianotyler/Excel_Analysis_Projects/Resources/Outcomes_vs_Goals.png
  - We see that fundraising goals under $1000 are extremely successful with a success rate of 76%. However, goals between $1000 and $4999 are almost as successful with a success rate of 73% with a majority of the projects falling into these two categories. Additionally, fundraisers with goals between $35,000 - and 39,999 and between $40,000 - 44,999 were almost as successful. Both with a sucess rate of 67% with a significantly smaller sample size.

### Challenges and Difficulties Encountered
  - The difficulties encountered came with collecting data for both Launch dates and Goals. For the launch date analysis I create a pivot table, filtering for Category and years. I wanted to compare the months to each other and only had the Start. I was able to overcome this difficulty by grouping dates together to form months using the group function in Excel. This gave me the information needed to complete the analysis. 
  - For the outcomes based on goals analysis, I ran into some trouble when dealing with the countif funciton when creating the Goal Ranges. I found that utalizing the >= notation when creating criteria would be critical to collect all the data needed to complete this analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - We can conclude that the most opportunistic time for theater projects to begin fundraising is in MAY. 
    - However, if you cannot start fundraising in my, the summer is the best season to fundraise (June, July, and August), with June being the next best option.

- What can you conclude about the Outcomes based on Goals?
   - We can conclude that fundraisers with Goals that are less than $5,000 are more likely to be successful.

- What are some limitations of this dataset?
   - We are limited by our relatively small sample size. There are only 1369 out of 4113 projects that are relavent to this analysis which will limit our findings. 

- What are some other possible tables and/or graphs that we could create?
   - I would create an a graph that shows the subcatgory "play" outcome vs launch date. This would give a better idea of when the best time was for Louise to start her fundraiser. You would only have to filter by subcatagory instead of category when conducting the Outcomes Based on Launch date analysis. 
