# Module 1 Challenge - Analysis of Kickstarter Data through Excel

## Overview of Project

The purpose of this project was to sift through previous Kickstarter Data to discover any trends there may be on the effect of the launch date and funding goals on the outcome of the Kickstarter. 

This may help us make more informed decisions on any future Kickstarter endeavors.


## Analysis and Challenges

#### Analysis

The analysis was done through Excel using Pivot Tables and Pivot Charts to isolate the parameters in question so that we may attempt to parse meaningful information from them. 


#### Challenges

The primary challenge that I ran into was my reading comprehension as I had spent a significant portion of my time of this challenge wondering how to get the job done using the excel function COUNTIF() rather than COUNTIFS(). Some other possible challenges that could be faced is the use of grouping to split the dates into relevant months. 

## Results

#### Theater Outcomes by Launch Date
![Theater Outcomes Based on Launch Date](/resources/chart1.png)

Figure 1 shows a comparison between the success of a kickstarter to the launch date. The primary takeaway from this visualization is that there are noticably more successful kickstarters between the months of May and July, despite there being no significant raise in failures in teh same time period. This would indicate that the success chance of Kickstarters during this period are higher as well.


#### Outcomes based on Goals
![Outcomes Based on Goals](/resources/chart2.png)

Here we see that there is a negative trend with regards to the increase in funding goals to success chance, with the exception of the 35000 to 45000 dollar range. This intuitively makes sense as it is easier to complete a funding goal that is smaller. But, starting a kickstarter with a low goal just to increase the chances of success leaves you with less resources to complete the project you have promised. 

I would personally regard the 35000-44999 range as an outlier as the number of data points is very low with only 9 total projects in that range. 


#### Limitations and Recommendations

The first dataset "Theater Outcomes by Launch Date" lacked visualization of percentages that clearly shows the chances of success increasining during the months of May to July. The value of successful kickstarters could have just been a factor of total number of kickstarters increasing during that period of time. I would recommend a second charge to show the percentage of outcomes based on launch date. 

Similarly, the second visualization does not really account for not having enough data points for $25000 onwards, and increasing the chance for outliers to skew the data. My recommendation for this would be to move the maximum bracket (i.e. "50000 or More") to 35000 or even 30000 so that the entire group can collect enough data points. 
