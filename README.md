# NBA_MVP_Projections
In This project, different methods were used such as web scraping, data cleaning, data exploration, regression and random forest 
Our file project contains 3 files in the following order: MVPS_WEBSCRAPING_AND_PREDICTIONS, Data_cleaning_MVP and Machine_learning_MVP

In the first file # "MVPS_WEBSCRAPING_AND_PREDICTIONS":
Webscraped data from basketball reference website from 1991 to 2022 by using BeautifulSoup and locating the tables and turning them into dataframes then saving them into a csv file
Downloaded Selesium since we are dealing with javascript encoded website to download the player data and team data that we combined with our mvp data 


In the second file # "Data_cleaning_MVP":
Dealing with duplicate rows especially the ones that been traded up during a specific season as they mught have multiple team within it. 
Combining Players and mvps datasets on player and year which are the common columns from both datasets.
Cleaning the Team file by removing unecessary rows but also created a new file with the team name and abbreviation to be able to combining with our previous dataset containing players and mvps "Combined".
Remove all the missing data after our merge and making sure that every column has the same data type "Float64"
Data exploration 

In the third file # "Machine_learning_MVP":
Performing data manipulation - Data cleaning 
Training our machine learning model - seperating train and test data 
using Ridghe regression as it is design to prevent overffiting
Identifying an error metric
Implimentinf back testing to predict each year
Diagnosing model performance
Use Random Forest
