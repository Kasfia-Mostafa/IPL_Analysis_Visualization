# IPL 2022 Capstone Project

## Project Overview
The Indian Premier League (IPL) is a professional T20 cricket league in India, featuring franchises representing cities. This project explores IPL 2022 match-level data to derive meaningful insights and understand match outcomes, player performances, and team dynamics.

## Dataset Description
The dataset contains match-level information from IPL 2022 with the following key columns:

| Column Name            | Data Type  | Description                          |
|------------------------|------------|--------------------------------------|
| date                   | string     | Date of the match                    |
| venue                  | string     | Stadium where match was played       |
| stage                  | string     | Stage of tournament (group/playoff)  |
| team1                  | string     | First team                           |
| team2                  | string     | Second team                          |
| toss_winner            | string     | Team that won the toss               |
| toss_decision          | string     | Decision to bat or field             |
| first_ings_score       | integer    | Score by team batting first          |
| second_ings_score      | integer    | Score by team batting second         |
| match_winner           | string     | Winning team                         |
| won_by                 | string     | Won by runs or wickets               |
| margin                 | integer    | Victory margin                       |
| player_of_the_match    | string     | Player awarded Man of the Match      |
| top_scorer             | string     | Highest scorer in the match          |
| highscore              | integer    | Highest individual score             |
| best_bowling           | string     | Best bowler in the match             |
| best_bowling_figure    | string     | Best bowling figures                 |

## Key Analyses

### Team Performance
- Which team won the most matches?
- Toss Decision Trends
- Toss Winner vs Match Winner
- How do teams win? (Runs vs Wickets)

### Player Performance
1. Most "Player of the Match" Awards
2. Top Scorers in the tournament
3. Best Bowling Figures

### Venue Analysis
- Most Matches Played by Venue

### Custom Questions & Insights
1. Who won the highest margin by runs?
2. Which player had the highest individual score?
3. Which bowler had the best bowling figures?

## Getting Started
1. Clone this repository
2. Install required libraries (pandas, numpy, matplotlib, seaborn)
3. Run the Jupyter notebook to explore the analysis

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
