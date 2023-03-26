# T20_WorldCup_Analysis
Built a Dashboard for T20 World Cup.

-  [**OVERVIEW**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/edit/main/README.md#overview)
-  [**DATA OVERVIEW**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/edit/main/README.md#dataoverview)
-  [**FRMEWORK**](https://github.com/ananyasaxenaaa23/T20_WorldCup_Analysis/edit/main/README.md)


## Overview
This Dashboard has been built to do the player Analysis and to see what all players are suitable for T20 World Cup. This Dashboard consists of 5 Categories and all these categories are Openers, Anchors, Finishers, All Rounders and Fast Bowlers.
Each category has its own Analytical Dashboard. Each player has its own category and their Analysis has been done using this Power BI Dashboard.



## Data Overview
The data has been extracted from the ESPN cricinfo website (https://stats.espncricinfo.com/ci/engine/records/team/match_results.html?id=14450;type=tournament).



## Framework
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


