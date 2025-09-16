# IPL Data Analysis & Insights

## Project Overview
This project is an **Exploratory Data Analysis (EDA)** on the Indian Premier League (IPL) dataset sourced from Kaggle. The goal is to analyze player performances, team statistics, and match outcomes over multiple seasons, and extract actionable insights for understanding trends and patterns in IPL cricket.

---

## Dataset
The dataset consists of multiple CSV files:

| CSV File | Description |
|----------|-------------|
| `Player.csv` | Contains player details such as Player_ID, Name, DOB, Batting Hand, Bowling Skill, Country. |
| `Match.csv` | Contains match-level information like Match_ID, Season_ID, Teams, Match Winner, Venue. |
| `Ball_by_Ball.csv` | Ball-by-ball details including Runs scored, Extras, Wickets, Bowler and Batsman info. |
| `Player_Match.csv` | Player-wise performance in each match. |
| `Season.csv` | Season-wise details including Season Year. |
| `Team.csv` | Team information including Team_ID, Team_Name, and Team_Short_Code. |

---

## Project Steps

1. **Data Cleaning & Preprocessing**
   - Handled missing values in player details and match information.
   - Standardized columns and cleaned duplicates.
   - Filled missing team or player information with 'Unknown' for clarity.

2. **Data Merging**
   - Merged all relevant CSV files into a single `master_df`.
   - Used player IDs, match IDs, team IDs as keys for merging.
   - Created a unified dataframe ready for analysis.

3. **Aggregations & Metrics**
   - Aggregated player stats: matches played, runs, wickets, batting hand, etc.
   - Calculated team performance metrics: total wins, top-performing players.
   - Derived additional insights like most common batting hand, bowling skills distribution.

4. **Visualizations**
   - **Top Scorers:** Horizontal bar charts for player runs.
   - **Team Wins:** Bar charts showing teams with most wins.
   - **Player Roles:** Pie chart for batting hand distribution.
   - **Bowling Skills:** Count plots for bowling styles.

5. **Insights**
   - Right-handed batsmen dominate IPL.
   - Fast bowlers and right-arm bowlers form the majority of bowling profiles.
   - Certain teams consistently outperform others in total wins.
   - Player performance patterns vary across seasons, highlighting key contributors.

---

## Libraries Used
- `pandas` – for data manipulation and aggregation  
- `numpy` – for numerical operations  
- `matplotlib` – for plotting charts  
- `seaborn` – for advanced visualizations  

---

## How to Reproduce
1. Clone this repository:  
```bash
git clone https://github.com/username/IPL-EDA-Project.git
