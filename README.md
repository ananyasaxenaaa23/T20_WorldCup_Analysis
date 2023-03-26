# T20_WorldCup_Analysis
Built a Dashboard for T20 World Cup.

-  [**OVERVIEW**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/blob/main/README.md#overview)
-  [**DATA OVERVIEW**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/blob/main/README.md#dataoverview)
-  [**FRMEWORK**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/blob/main/README.md#framework)
-  [**DASHBOARD OVERVIEW**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/blob/main/README.md#dashboardoverview)
-  [**CONCLUSION**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/blob/main/README.md#conclusion)

# Overview
This Dashboard has been built to do the player Analysis and to see what all players are suitable for T20 World Cup. This Dashboard consists of 5 Categories and all these categories are Openers, Anchors, Finishers, All Rounders and Fast Bowlers.
Each category has its own Analytical Dashboard. Each player has its own category and their Analysis has been done using this Power BI Dashboard.



# Data Overview
The data has been extracted from the ESPN cricinfo website (https://stats.espncricinfo.com/ci/engine/records/team/match_results.html?id=14450;type=tournament).



# Framework
The Framework consists of a few steps.

## 1. Web Scraping
The data was extracted from the ESPN site mentioned above with the help of Web Scraping in JavaScript as it makes the data extraction easy. The data extracted using JavScript will be available in the form of json files.

## 2. Data Preprocessing
The data was pre processed to remove all the unnecessary elements present in the data including the unnecessary symbols. Also, the data files were converted into CSV format and all the data pre processing was done using Python. 

## 3. Data Transformation
After converting the data into csv files the remaining transformations on data were done using Power BI Query. Data Transformation includes changing the column names, column values and also changing the String values into numerical values and vice versa if needed. 

## 4. Data Modeling
Data Modeling includes connecting the different data fieldswith each other and to create different methods. Several methods were used for creating different measures like, Average, Sum, Dot Ball % and many more.

## 5. Building a Power BI Dashboard
After all the steps mentioned above the data was visualized using Microsoft Power BI. Different insights were generated after the visualization was done.



# Dashboard Overview
The first Dashboard shows the Player Analysis of Middle Order Players which consists of the runs, team, batting style, balls faced, Innings Batted by them and many more of following players mentioned in the table.
The scatter plots show their Batting Average, Average Balls Faced, Strike Rate and Boundary % with respect to Match Day in the form of Plots.
![image](https://user-images.githubusercontent.com/70996037/227791950-afbbdf80-7614-4fe6-98f8-6555b5ac13af.png)

The second Dashboard shows us the Player Analysis of Openers which consists of the runs, team, batting style, balls faced by them and many more of following players mentioned in the table. 
The scatter plots show their Batting Average, Average Balls Faced, Strike Rate and Boundary % with respect to Match Day in the form of Plots.


# Conclusion
The conclusion drawn from this dashboard is that which players are suitable for player T20 World Cup amongst the players all over the world.
