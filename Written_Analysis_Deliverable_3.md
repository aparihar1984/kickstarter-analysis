# Kickstarting with Excel
Building my knowledge of MicroSoft Excel by examining different funding goals for plays.
## Overview of Project
I created two different line charts using Pivot Tables and Pivot Charts, along with various formulas and functions such as countifs and percentage calculations.  The first line chart represents whether the funding campaigns for each play succeeded, failed, or was canceled based on their respective launch dates.  The second line chart represents whether the funding campaigns for each play succeeded, failed, or was canceled based on each plays funding goal amount.
### Purpose
Using my knowledge of MicroSoft Excel to examine different funding campaigns for various plays based on their repsective launch dates, and whether the respective funding goals for each play were successful or not. 
## Analysis and Challenges
Using module lessons [1.3.1: Creating a pivot table] (https://bootcampspot.instructure.com/courses/193/modules/items/50229) and [1.3.2: Create a chart from a pivot table] (https://bootcampspot.instructure.com/courses/193/modules/items/50230), I was able to create both a pivot table and a line chart plotting the number of successful, failed, and canceled outcomes corresponding to each month of the year.

The challenge in creating this pivot table and line chart was how to properly understand all the pivot table fields and how to properly fill the various areas (Columns, Values, Rows, and Filters).  Placing the wrong fields into the wrong areas often leads to an inability to properly gauge and examine the data.  This can hinder one's ability to determine whether the purpose of the exercise was accomplished properly.

Using the countifs function, I was able to create a table and line chart displaying the successful, failed, and canceled number of plays based on the funding goal amounts.  Instead of plotting against the months of the year as in the previous line chart, I broke down the goal amounts into ranges (<1000, 1000-4999, etc...) then used the countifs function to determine every successful, failed and canceled play in each funding goal range.  Percentages were then determined for all the successful, failed and canceled plays in each range. 

Although there were no diffculties in creating this "based on goals" line chart, it is very important to understand how to use the countifs function when filtering and entering the various ranges.  Improper use of the countifs function will lead to a poorly constructed table and inaccurate readings of data.
### Analysis of Outcomes Based on Launch Date

./Resources/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals

./Resources/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered
As mentioned before, understanding the various fields and what they mean when creating the pivot table was the most challenging step.  Understanding what the x-axis of a line chart represents, and what the y-axis of a line chart represents allowed me to understand how to populate the areas (Values, Outcomes, Rows and Filters) for the Theater Outcomes Based on Launch Date pivot table.  This allowed me to create a corresonding line chart that was easy to follow and understand/intrepret the data points.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Two conclusions that can be drawn from the Theater Outcomes are that the highest number of successful campaigns came in May, June, and July, and that the number of canceled plays remained relatively constant throughout the year (at least compared to the number of successful and failed outcomes).

Why was this the case?  Perhaps the warmer weather in the summer could be a factor.  People tend to go out more in the summer and entertainment options such as theatrical plays and movies tend to do their best business during the summer season.  Perhaps greater demand leads to more successful campaigns.

- What can you conclude about the Outcomes based on Goals?

The obvious conculsion of the Outcomes Based on Goals table and line chart is that the number of successful and failed plays both decline dramatically as the funding goals/ranges increase.  The number of successful and failed plays are only in single digits once funding goals/ranges are above $20,000.  The relatively small samples/numbers of plays lead to larger variances/swings with the percentages which is shown on the corresponding line chart.

- What are some limitations of this dataset?

The dataset used produced two line charts that can display a specific result, but can't necessarily explain how or why that result came to be.  For example I mentioned earlier that the number of successful campaigns based on launch dates came during the summer months.  Although we can make educated guesses as to why that is, these are still guesses.

Another limitation may be potential small sample sizes which often lead to large variances or swings in the line charts.  This often happens when examining small samples of data.

- What are some other possible tables and/or graphs that we could create?

Instead of using "theater" as the only Parent Category and "plays" as the only Subcategory in the line graphs and tables, we could perhaps use other Parent Categories such as "film and video" or "journalism" in connection with other Subcategories such as "animation" or "audio".  

We could then contrast and compare these line graphs and tables with the "theater/plays" Parent Category/Subcategory to see any potential differences.  Does one Parent Category/Subcategory produce more successful funding campaigns?  How much of a factor does time of year play into funding campaigns for "journalism"?  These are questions we can examine by comparing more categories in addition to the "theater" and "plays" categories.