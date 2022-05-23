# kickstarter-analysis #

## Project Overview

Analysis on Kickstarter data to uncover trends on successful, failed and canceled projects, specifically with theater projects.

## Analysis and Challenges

* Dataset was not well formated to begin with so changes were made to color coordinate the outcomes column; with green meaning successful, yellow as canceled, blue as live, and failed as red (pictured below).
* ![Screen Shot 2022-05-23 at 12 01 21 PM](https://user-images.githubusercontent.com/96406929/169888519-38e2dfbc-fdf5-4415-b355-f4c906f5897c.png)
* Several columns were also added to the spreadsheet to track projects percentage funded, average donations, parent category and subcategory.
* Two additional columns of conversions were added as a challenge I ran into was the the date created and date ended columns in the spreadsheet being in UNIX time format, as a result Date Created Conversion and Date Ended Conversion columns were added. (Pitcured Below)
* ![Screen Shot 2022-05-23 at 12 10 23 PM](https://user-images.githubusercontent.com/96406929/169889718-00ae434f-820f-4bb8-b3ba-c639d0466718.png)
* Once data was formated, a pivot table and pivot chart were created to show the outcomes of theater projects based on start date. (Pictured below)
* ![Screen Shot 2022-05-23 at 12 12 06 PM](https://user-images.githubusercontent.com/96406929/169890154-599c937f-847a-482d-97e6-9e84d30d51aa.png)
* An additional worksheet and chart were also created to show the outcomes of plays based on their monetary goals on kickstarter. (Pictured below)
* ![Screen Shot 2022-05-23 at 12 15 42 PM](https://user-images.githubusercontent.com/96406929/169890746-98c2dcbe-70c5-407f-8f4f-8da931d2d5f3.png)

## Results

Based on the Theater Outcomes by Launch Date pivot chart one conclusion that can be made is that June is the best month to create a theater campaign as that seems to be the month with the most success. Another conclusion that can be made about the Theater Outcomes by Launch Date chart is that October through December would be the worst time of year to create a campaign as they are less successful in those months. When it comes to outcomes based on goals, our chart shows us that lower financial goals seem to be the most successful while projects asking for $15,000 tend to fail more. Our dataset did face some limitations such as who created the kickstarter campaign, and there were also quite a bit of outliers under our percentage funded column. I believe this analysis would benefit from an additional pivot chart showing how subcategories of plays did compared to others (i.e. musicals vs comedies). I also think a pivot table showing the difference in theater kickstarters being funded by country would be beneficial to the analysis.



