# IADAI204-1000308-AbhinavChanakya
****IPL Cricket Data Analysis – Decoding Match-Winning Factors****

** *Project Overview***

This project evaluates the information of Indian premier league (IPL) cricket in an attempt to identify the most important factors that determine the result of matches. With the help of Tableau, an interactive dashboard was created that will be used to assess the performance of players, rivalry between teams, and other situational factors of the match like toss and venue influence.

The main objective of the project is to reveal practical recommendations to the IPL franchises, coaches, broadcasters and cricket enthusiasts since it converts the raw ball-by-ball and match-level data, into useful visual narratives.

** *Data Summary***

The samples of the dataset employed in this project comprise:

matches.csv - List of matches (season, venue, teams, winner, details of the toss, etc.)

deliveries.csv - ball-by-ball information (runs, wickets, batsman, bowler, type of dismissal, etc.)

Tableau was used to join the two datasets on:

matches.id = deliveries.match_id

A Join Inner was used to exclude any deliveries that were invalid based on match.

Data Preparation Steps:

Monotonous non systematic names of team (e.g., Delhi Daredevils - DelhiCapitals).

Managed missing values in fields winner and playerofmatch.

Formulated calculated fields of sophisticated measures:

Strike Rate

Economy Rate

Wickets (excluding run-outs)

Checked data forms and guaranteed adequate aggregation in Tableau.

** *Key Insights*
**
Total runs and strike rate have been used as a measure of consistency as well as impact to determine the top batsmen.

Top bowlers were examined in terms of efficiency in terms of wickets taken and economy rate.

Toss decisions were found to have different impacts in the seasons, especially at certain venues.

Some of the venues showed good patterns of home-ground advantage.

The analysis conducted on head to head rivalry showed dominant franchises in given matches.

** *Dashboard Features***

The Tableau dashboard has:

Interactive filters for:

Season

Team

Player

Venue

Comparison of performance in players (batting and bowling).

Team rivalry heatmaps.

Seasonal trend of toss decision.

Analysis of match result based on the venue.

Interactive graphs containing drill-down and tooltip tips.

The dash board aims at making the users have a flow of story telling in a logical way:
Researcher Performance - Club Competitiveness - Winning Matches Insights - Key Findings.

 ***Tableau Public Dashboard***

 Marble public Tableau Public link insertion.

Example:

[IPL Statistics Data Analysis – Decoding Match-Winning Factors | Tableau Public](https://public.tableau.com/views/IPLStatisticsDataAnalysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

** *Repository Structure***
+-- data/
    +-- matches.csv
    +-- deliveries.csv
+-- IPLCricketAnalysis.twbx
+-- README.md

Important: CSV-files can only be uploaded as raw and not as gz because of memory constraint in github. The data is internally stored in the packaged Tableau workbook (.twbx).

** *Conclusion***

This project shows that the integration of player-level statistics with the contextual match data can further explain the results of the IPL matches. Through the interactive graphical storytelling, stakeholders will be in a position to establish the trends in the performance of players, matches rivalry, and team strategic choices.

The improvements can be made in the future and they should include:

Forecasting result of matches.

Breakdown of performance-over wise.

Powerplay death-over impact analysis.

Win probability modelling

 ***Technologies Used***

Tableau Public (Charting & Dashboard)

CSV data (Structured cricket data).

GitHub ( Documentation and Version Control of the Project)

<img width="1243" height="810" alt="image" src="https://github.com/user-attachments/assets/a62b605c-0559-4c2b-bfe3-ff59be2bc1ed" />
