# Kickstarting with Excel

## Overview of Project
Our client Louise wants to know how different theater campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset we visualized the campaign outcomes based on their launch dates and their funding goals so we can get a better understanding of the data provided. after combing through, organizing and visualizing the data my understanding is that for best chance of success the fundraiser event should launch in May. One discovery I found very surprising is that the month of december had one of the lowest success rates despite it being the season of giving. fundraisers were not very successful during the holiday season.

### Analysis of Outcomes Based on Launch Date

As the chart shows May is the best month to launch a fundraiser event followed by June then April and July.
Surprisingly the holiday season is the worst time to launch a fundraiser event due to the lower success rate, However this may be due to the lower number of events launched in December overall.

### Analysis of Outcomes Based on Goals

Fundraiser events with goals under $1000 have the highest rate of success and events with a goal of 50k+ usually having the lowest. the amounts in between make it seem like the goal amount is irrelevant but if you look at the bigger picture you can see that fundraiser events with lower goal amounts are more likely to be successful.

### Challenges and Difficulties Encountered

during the analysis I ran into a problem when using "countifs" after hours of google searches i realized i was not typing the "s" and was only typping "=countif" a simple small error that i kept overlooking because i was sure i am typing it correctly wasted 3 hours of my time.
another problem i ran into was while making the pivot table to analyze the outcomes based on launch date. when trying to add "years" to the row(axis) tab the table would display years (2009,2010,2011,2012,...) on the row axis instead of the months that i want it to. when I tried to ungroup it i was repeatedly stopped by an error message stating "value does not exist". upon further digging i uncovered this is due to the fact that my "years" colomn on the kickstarter sheet was named "year". 

### Limitations and other possible charts
If time premitted i would love to add a chart that shows the average donation amount or the pledged amount per month to see during what time of the year people are most giving it can be used in conjunction with "Outcomes based on Launch Date" to compare the success rate and to see if wether or not the month of May truly is when people are most giving or is there a spike in successful fundraiser due to the fact that there are more fundraisers.

## Results
As the data concludes May is the best time to launch a fundraiser event and i would recomend to not have the goal amount set unreasonably high. 
