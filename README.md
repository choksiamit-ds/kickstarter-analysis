# kickstarter-analysis

## Overview of Project

This project is about performing data analysis on a data set from various fund raising campaigns and how they fared in relation to their launch dates and funding goals. The purpose of this analysis is to provide data to help design future fund raising campaigns by learning from the success and failures of the campaigns in this Kickstarter dataset. There are various factors that determine the success of any campaign. 

This project analyses outcome of the fundraising campaign in specific category /subcategory based on Launch Date and Launch Goals. This will help future campaigners to determine the right time to launch it, set the right amount of goals to ensure a high success rate based on past success and failures. The analysis can be extended for various specific categories and subcategories.

## Analysis and Challenges

<img width="513" alt="image" src="https://user-images.githubusercontent.com/103329721/163754011-f4ba0ce1-a04e-41d0-8803-88f9bdce4c20.png">

The above line chart shows the percentage of successful, failed and canceled projects based on month of the year.
Some inteferences are Success rates are higher between the months of April and May, Success rates gradually dip from May until December. It gradually picks up from January with a gradual dip in the month of March. The number of canceled projects is fairly constant with an exception of the month October, it has zero canceled projects.

<img width="793" alt="image" src="https://user-images.githubusercontent.com/103329721/163754368-30c8b2ba-798f-4384-8114-ac1be65752b2.png">

The above line chart shows outcome of percentage failed, canceled and successful campaigns in the subcategory of play and projected goals classified in various categories ( Less than 1000, 1000 to 4999 .. until Greater than 50000 ). The highest success categories are in Less than 1000 and $30000 to $40000 goals. The success rate steeply goes down in the category of 45000 - 49999 and above with a minor 13% increase in success rate for the range above $50000 

Challenges encountered in this project were mostly related to discovering various features in Excel like sorting rows based on custom lists, defining how the cell values should be interpreted based on the specific target ( Percentage, general, numeric etc ). I tool help from tutor, asked the class group, used google search for some specific difficulties. Some of the difficulty I encountered were specific to Mac ( used for this project ) 

## *Results*

### Conclusions based on Launch Date ###
1. Success rate is higher in summer months
2. Cancel rate is fairly constant in all months with an exception of zero in the month of October
### Conclusions based on Outcome based on Goals ###
1. There is an above 50% success rate for this data set if the goals were below 20000. This is the breakeven point and beyond this the failure rate goes higher than the success rate.


### Summary of Limitations ###

1. The dataset is distributed across a wide geography, some categories and sub categories may be more or less popular in different cultures so it is not the most accurate way to predict future campaigns unless the data is filtered for the nation of interest.
2. This dataset does not take into account any political disturbances, financial situation of the nation, stock market downturn, natural calamities which may have led to some campaign failures.
#### Recommendation for additional tables or graphs
1. Nation specific analysis based on launch dates
2. Specific Category/Subcategory across all nations.
3. Nation specific success failure rates.
