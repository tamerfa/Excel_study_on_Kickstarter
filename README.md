## An analytic study on Kickstarter

## Overview:
Kickstarter.com is the website where creative project ideas meet their funding enthusiasts. Every entrepreneur applying at this website has a certain financial goal that needs to be met or exceeded to succeed and be able to initiate their project. 
Unfortunately, out of more than 300,000 projects launched on kickstarter.com, nearly 100,000 projects only have made it to success. So, it is necessary for anyone wishing to apply for a new project on Kickstarter to study the statistics of the past projects to understand the factors that affected their success and to maximise their chances of achieving their own success.
In this study, I have used a dataset of more than 4,000 past projects to try and discover any trends that can be used to guarantee success when launching a project on Kickstarter.
## Model:
The dataset provided contains data about 4,114 projects launched between the years 2009 and 2017 in over 20 countries, their categories and sub-categories, number of backers and how much they raised compared to the projects’ original goals indicating success or failure of the campaigns.
In this study, I have created from this dataset three pivot charts:
1)	A bar chart showing the count of successful, failed, cancelled and live campaigns based on their categories.
 ![category-stats](/Images/category-stats.png)
2)	A bar chart showing the count of successful, failed, cancelled and live campaigns based on their sub-categories.
 ![subcategorystats](/Images/SubcategoryStats.png)

3)	A line chart showing the count of successful, failed and cancelled projects based on the month of the year
 ![line-chart](/Images/line-chart.png)

## Conclusion:
After studying the previous charts, I reached the following conclusions:
1)	Campaigns of some subcategories were all successful without any failures, such as short films and videos, documentaries, some types of music, tabletop games and hardware technology.
2)	All campaigns of certain subcategories have failed or cancelled, such as drama, animation videos, video games, children’s books.
3)	Campaigns launched at the months of April and May had a greater chance of success, while those launched at the months of December and January had a greater risk of failure with the number of failures has even surpassed the number of successes in December.

## Limitations:
Although this dataset was very useful in studying success and failure rates on Kickstarter, it has its limitations:
1)	It did not include the projects launched in the recent years after 2017.
2)	As the currencies used are different, we had no way of comparison for the finances of the campaigns. For example, the current price of Hong Kong Dollar is 0.13 US Dollar, so a project goal of HKD 70,000 may look at first hard to achieve, but in reality, it is just less than USD 9000.

## Further tables or graphs:
Other graphs can be created from this dataset, such as:
1)	Using conditional formatting, we can create the heat map below with countries in rows, categories in the columns and state in the values to study which campaign categories are more likely to be launched in each country.
  ![heatmap](/Images/heatmap.png)

2)	We can add a column to the dataset to convert all currencies to a unified base currency (Indicative only as conversion rates change).
3)	We can create a pivot table with the categories in the columns, subcategories in the rows and average percentage funded in the values, then by filtering each category we can draw pie charts showing the distribution of funding for the subcategories of each category like the example below.
 ![pie-chart](/Images/pie-chart.png) 
4)	We can create a pivot table and a bar chart showing the state of campaigns per country.

