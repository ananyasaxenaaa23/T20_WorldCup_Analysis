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
The first Dashboard shows the Player Analysis of Middle Order Players/Anchors which consists of the runs, team, batting style, balls faced, Innings Batted by them and many more of following players mentioned in the table.
The Area charts show their Batting Average, Average Balls Faced, Strike Rate and Boundary % with respect to Match Day in the form of Plots.
The scatter plot shows Batting Average with respect to the Strike Rate of the players mentioned.
![image](https://user-images.githubusercontent.com/70996037/227791950-afbbdf80-7614-4fe6-98f8-6555b5ac13af.png)

The second Dashboard shows the Player Analysis of Openers which consists of the runs, team, batting style, balls faced by them and many more of following players mentioned in the table. 
The stacked area chart shows their Batting Average, Average Balls Faced, Strike Rate and Boundary % with respect to Match Day in the form of Plots.
The scatter plot shows Batting Average with respect to the Strike Rate of the players mentioned.
![image](https://user-images.githubusercontent.com/70996037/227793166-9179f7ec-153e-49a2-9091-4c45ceda9d0f.png)

The third Dashboard shows the Player Analysis of Finishers which consists of the runs, team, batting style, balls faced by them and many more of following players mentioned in the table.
The stacked area chart shows their Batting Average, Bowling Strike Rate, Strike Rate and Economy with respect to Match Day in the form of Plots.
The scatter plot shows Batting Average with respect to the Strike Rate of the players mentioned.
![image](https://user-images.githubusercontent.com/70996037/227793278-62c93dfe-89f8-48ab-a542-fb1689fcfeff.png)

The fourth Dashboard shows the Player Analysis of All Rounders which consists of the runs, team, batting style, balls faced by them and many more of following players mentioned in the table.
The stacked area chart shows their Batting Average, Strike Rate, Bowling Strike Rate and Economy with respect to Match Day in the form of Plots.
The scatter plot shows Bowling Strike Rate with respect to the Economy of the players mentioned.
![image](https://user-images.githubusercontent.com/70996037/227793754-e46a49e2-a6e7-41a4-a46c-b3a98cf5705a.png)

The fifth Dashboard shows the Player Analysis of Fast Bowlers which consists of the runs, team, batting style, balls faced by them and many more of following players mentioned in the table.
The stacked area chart shows their Bowling Average, Dot Ball %, Bowling Strike Rate and Economy with respect to Match Day in the form of Plots.
The scatter plot shows Bowling Strike Rate with respect to the Economy of the players mentioned.
![image](https://user-images.githubusercontent.com/70996037/227794139-2b4c0f9a-d7da-46cc-9515-d74c673cbbcb.png)

The last Dashboard shows a Table consisting of Final 12 players choosen on the basis of all the Analysis done.
![image](https://user-images.githubusercontent.com/70996037/227794192-f7bc8400-8b5d-46dc-89ed-c7e1dd9030ca.png)



# Conclusion
The conclusion drawn from this dashboard is that which players are suitable for player T20 World Cup amongst the players all over the world.
