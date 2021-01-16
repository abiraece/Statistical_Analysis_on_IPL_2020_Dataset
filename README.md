# Statistical_Analysis_on_IPL_2020_Dataset
Data Analysis -on-IPL-Dataset

Table of Content:
1. Project Introduction
2. Dataset Description
3. Data Preprocessing and Encoding
4. Statistical Analysis

IPL 2020
Now that this year's IPL is over, let's not curb our cricket love and start analyzing the whole of IPL with this latest and complete Indian Premier League dataset. It contains the match descriptions, results, winners, player of the matches, ball by ball dataset and much more. So, stop thinking and start analyzing .

Content
This dataset consists of four seperate CSV files : Batsman,Bowler,Team_player,Point_table. These files contain the information of each match summary and ball by ball details, respectively.

Data Description on Batsman File:

POS : Position

PLAYER : Name of the Player
    
Mat : Number of Matches Played
    
Inns : Inns played
    
NO : NOT OUT in number of Matches played
    
Runs : Number of Runs Scored 
    
HS : Highest Score ever made by the batsman.
    
Avg : Average runs scored throught out the ipl 2020 (670 / 14)

BF : Ball Faced (Total number of balls received, including no-balls but not including wides)
    
SR : Stike Rate ( Avg number of runs scored per 100 ball faced) High stike rate, more effective batsman
    
100 : Number of 100 scored in each match
    
50 : Number of 50 scored in each match
    
4s : Number of 4s in each match
    
6s : Number of 6s in each match

Description about Bowler Dataset

PLAYER : Name of the Player

Mat: no.of matches
    
Inns : no.of matches

Runs: Runs given in overall IPL

Ov : Overs bowled

Wkts : Total number of wickets

BBI : Best Bowling Inning (maximum wickets with lowest run)
  
Avg : Number of runs they have conceded per wicket taken. Lower the bowling average, better bowler performing

Econ : Avg number of runs they have conceded per over bowled. Lower economy rate, better bowler performing.

SR : Avg number of balls bowled per wicket taken. Lower strike rate, effective bowler taking wickets quickly

4W : 4 wickets in each match

5W : 5 wicktes in each match


Data Preprocessing:

Intially in all above four datasets some null values and special characters are there. For further Analysis different encoding and null value imputation methods are carried out.
After Data Preprocessing, Data Analysis was made on each dataset:

In Batsman Dataset, find out player name on different condition: player who scored highest run and not-out throughout IPL 2020, Player who scored more number of 6 and 4, is there correlation exist between stike rate and runs and many more.

Similarly in Bowler Dataset, we found player name who got more wicket and gave minimum runs, player name with highest BBI, and ploted distribution of stike rate of bowlers and many more

Statistical Analysis:

One Sample Mean and Proportion test is performed in the Batsman dataset, we can conclude that:
1.	Mean of average run scored by batsman in IPL 2020 is not equal 50.
2.	Mean Stike Rate of the player is not equal to 110.

In case of Two sample Mean and Proportion test performed in the Batsman dataset, we can conclude that:
1.	High Score has effect on Average run scored,Ballfaced,StikeRate
3.	Batsman Out High Score is equal to Batsman Not-Out High Score.
4.	Batsman Run has effect on Stike Rate in IPL 2020

One Sample Mean and Proportion test is performed in the Batsman dataset, we can conclude that:
1.	Mean Stike Rate of Bolwer in IPL 2020 is > 13
2.	Mean Economy of Bowler > 8

In case of Two sample Mean and Proportion test performed in the Batsman dataset, we can conclude that:
1.	Stike Rate has effect on Economy, Average of Bowler in IPL 2020.
2.	BBI has effect on Stike Rate of Bowler in IPL 2020.
3.	Bowler wicket has effect on BBI in IPL 2020.



