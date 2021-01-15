# Analyses-of-IPL-dataset-


Description of Dataset:
       IPL Dataset: The dataset consists of data from year 2008 to 2016. The league has 8 teams representing 8 different Indian states. The dataset consists of following columns
'id', 'season', 'city', 'date', 'team1', 'team2', 'toss_winner','toss_decision', 'result', 'dl_applied', 'winner', 'win_by_runs','win_by_wickets', 'player_of_match','venue', 'umpire1', 'umpire2','umpire3'.
       Batsman Dataset: The dataset consist of the statistics of a player. The dataset consists of the following columns:
       'POS', 'PLAYER', 'Mat', 'Inns', 'NO', 'Runs', 'HS', 'Avg', 'BF', 'SR','100', '50', '4s', '6s', 'Team'.

OBJECTIVE:
        Coded supervised regression algorithm to predict the strike rate of a given player and visualized the most valuable team and player.
        
The data was read using pandas library. Performed data cleaning and data analysis using python, created data visualization using seaborn, matplotlib and drew conclusion from the result of visualization. Some main objective of the study were,
                        1) to find total matches played in each ground,
                        2) to find statistics between given two teams,
                        3) to find most sucessful team,
                        4) to find how does the toss influence the match,
                        5) to find top batsman of a team,
                        6) to find most sucessful batsman of the IPL,
                        7) to find how weather can disturb the game in a specific pitch.
                      
                      
Performed Hypothesis testing (Z Test, P value method) to determine the plausibility of the hypothesis for the given IPL dataset. 
Z-test was performed for the hypothesis 
                        1) that the given specific team has won on an avearage of 6 matches per year,
                        2) that the given team has won by runs equal to or less than 50.
p value method was performed for the hypothesis
                        1) that the average number of sixes hit by a team is equalto or greater than 60 per year,
                        2) that the  average number of balls faced by a team is equalto or greater than 3000 per year.
                  
Linear regression model was modelled and the dataset was fit into the model. Predicted 
                        1) Total number of matches that will be won by batting first on a particular year using simple linear regression,
                        2) Strike rate of a particular batsman after 'n' matches using multiple linear regression.
