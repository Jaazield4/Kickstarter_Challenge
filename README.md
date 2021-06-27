# Kickstarting with Excel

## Overview of Project
  Using functions, pivot tables, and charts to determine successful, failed, and canceled kickstarter campaigns for a given subcategory and display visuals.

### Purpose
  The purpose of the Kickstarter_Challenge is to practice using excel functions to easily read and analyze specific data from a long spreadsheet.
  The project helped gain experience in properly using pivot tables to successfullly filter data from a large spreadsheet to a simple to 
  read table using the correct columns, rows, values and filters. By creating this pivot chart we were able to easily see the outcomes of kickstarter
  campaigns based on months. Using the countifs function we were also able to determine the percentage of successful, failed, and canceled campaigns
  with the subcategory "plays" for different goal ranges. By creating an easy to read chart, anyone who views the chart will be able to decipher the data quickly

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
  By creating a pivot table and chart to easily view the outcomes of campaigns by month we are able to see which month delivered the highest success. 
  We wanted to determine the outcomes by month for the parent category theater. By adding "parent category" as a filter and selecting theater we were able to 
  see that there were 37 canceled, 493 failed, 24 live, and 839 successful campaigns for a 12 month period. We then continued to create a chart of the table to
  visually see that there are more successful campains and very few canceled.
  
### Analysis of Outcomes Based on Goals
  Using the countifs function I was able to determine the number of successful, failed, and canceled kickstarter campaigns that fall under the subcategory "plays"
  from the "Kickstarter" worksheet based on 12 different goal amount ranges. For each goal range we determined the total amount of "plays" projects. Using a division 
  function we then found the percentage of outcome based on goal ranges, and created a line chart to display the relationship between goal range and percent of outcomes
  

### Challenges and Difficulties Encountered
  When conducting the analysis a challenge I encountered was properly using the countifs function. After some trial and error along with helpful videos I was able
  to find the correct function. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
-   The first conclusion we can draw is that the month with the most successful outcomes for theater projects came in the month of May.
-   The second conclusion is that December saw almost the same amount of fails as success making it the least ideal month to begin a campaign for theater.

- What can you conclude about the Outcomes based on Goals?
-   From the data gathered we can conclude that there were no "plays" projects canceled despite the goal range. We can also determine that the highest success
-   campaigns were those that had a goal under $1000. 

- What are some limitations of this dataset?
-   Some limitations based on this dataset is that when asked to determine outcomes based on goals the instructions went from <=49,000 to >50,000 meaning that
-   we do not have the outcomes for a goal of exactly 50,000. We also did not conduct any analysis to determine based on locatin.

- What are some other possible tables and/or graphs that we could create?
-   We could create a table based on location to determine the success rate of different projects based on country. We can also create a chart that shows the 
-   number of backers per category.
