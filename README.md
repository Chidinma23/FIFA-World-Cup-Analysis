# FIFA WORLD CUP ANALYSIS
![Screenshot 2023-04-14 004434](https://user-images.githubusercontent.com/115046602/231907258-3ded4efd-91b1-433c-87f6-900c7e7c2060.png)

# Introduction
The FIFA World Cup is an international association football competition contested by the senior men's national teams of the members of the Fédération Internationale de Football Association (FIFA), the sport's global governing body. The tournament has been held every four years since the inaugural tournament in 1930. The World Cup is the most prestigious association football tournament in the world, as well as the most widely viewed and followed single sporting event in the world. The viewership of the 2018 World Cup was estimated to be 3.57 billion (close to half of the global population).
# Project Name: FIFA World Cup 2022 Dataset
An analysis on the past FIFA world cup and 2022 data using PowerBi

# Project Objective: Analyze France World Cup History
This analysis is aimed at focusing on France, showing the story of the country's history with the World Cup, their road to Qatar, and their expectations for this year's tournament by using data visualization.

# Data Sourcing: Web Scraping
Data was gotten from the web and downloaded as a CSV file. This dataset contains 6 tables in CSV format. 
The World Cups table outlines each World Cups in history, including the year, host country, and winner. 
The 2022 World Cup Groups table includes all the qualified countries for this year's World Cup, the group they were drawn to, and their FIFA Ranking.
The 2022 World Cup Squads table includes the official squads for each team, including details on their goals and games with the national team.
The 2022 World Cup Matches table contains the date matches scheduled for the 2022 FIFA World Cup
The World Cup Matches table contains all the results from the previous editions of the World Cup
The International Matches table contains all het results from every international match in history outside of the World Cup for each qualified country

# Data Cleaning
# Microsoft PowerBi
The data was cleaned using Power Query editor and insights were visualized using PowerBi desktop

# Data Cleaning Process
Each column was observed and changed to their correct data types where necessary. For the international column, the yaer was separated from the Date into a new column.

# Building Relationships
After loading the data, relationships were created between the data sets in order to build model relationship that propagates filters applied on the column of one model table to a different model table. A new table was added to this dataset - Date table - This is the compilation of the dates from the earliest to the latest, for easy analysis. 

# PowerBi Desktop : Content Analysis
DAX maesures were applied by creating calculated measure/columns, using this, the following insights were collected for France: Total World cups, France Total World Cup wins, France World Cup wins as host, FIFA Ranking, Total World Cup Goals, Average Age, Goals and World cup goals by players, Goals by players by position, World Cup Goals by year, and France international goals by year.

# PowerBi Desktop : Summary Page
This page is filetered to compare and contrast history of France goals in the world cup to other countries.

# Conclusions
1. France has one (1) World cup win as host but has two (2) overall wins in its history of participating in the world cup
2. FIFA Ranking - No. 4
3. Total World Cup Goals - 120
4. Average Age - 26.54
5. No. of International Goals is 1,440
6. Oliver Giroud, Antonie Griezmann and Karim Benzema are the top goal scorers
7. By Position, the top goals are scored by the Foward (61.46%), Midfielder (27.26%), Defenders (11.28%)
