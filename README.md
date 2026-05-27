# ⚽ FIFA World Cup Historical Analytics

A data-driven analysis of FIFA World Cup history exploring attacking trends, tactical evolution, team dominance, and match entertainment patterns across nearly a century of football.

# Project Overview

This project analyzes historical FIFA World Cup match data to uncover insights about:

⚽ Which teams are the most dominant attackers
📉 How football tactics have evolved over time
🏟️ Whether “home-listed” teams perform better
🎉 Which tournaments are the most entertaining
🔥 Which matchups produce the highest-scoring games

The goal is to go beyond match results and understand the story football data tells over time.

# Dataset

Source: Kaggle Cleaned FIFA World Cup historical match data

Columns:
home – Home team
away – Away team
year – Tournament year
home_goals – Goals scored by home team
away_goals – Goals scored by away team
total_goals – Total goals in match
🧠 Key Analytical Questions

This project answers 5 core football business questions:

# 1. ⚽ Which national teams are the most dominant attackers?

We rank teams based on:

Total goals scored
Average goals per match
Consistency across tournaments

📌 Insight: Teams like Brazil, Germany, and Argentina dominate attacking metrics historically.

# 2. 📉 Has World Cup football become more defensive over time?

We analyze:

Average goals per match by year
Decade-level scoring trends
Evolution of tactical eras

📌 Insight: Football transitioned from high-scoring early eras to a more tactical, defensive modern game, with slight attacking recovery in recent tournaments.

# 3. 🏟️ Does “home-listed” status affect performance?

We compare:

Home vs away goals
Win rates for home-listed teams
Team-level home vs away differences

📌 Insight: Home-listed teams tend to perform better, but this is largely driven by team strength and tournament structure rather than true home advantage.

# 4. 🎉 Which World Cups were the most entertaining?

We measure entertainment using:

Average goals per match
Total goals per tournament
Goal intensity trends

📌 Insight: Early World Cups (especially 1954) were the most entertaining, while modern football shows a more balanced but still engaging scoring pattern.

# 5. 🔥 Which matchups produce the most goals?

We analyze team pairings to find high-scoring fixtures.

📌 Insight: Certain matchups like France vs West Germany and Brazil vs Poland consistently produce high goal totals due to stylistic clashes.

# Key Insights Summary
🥇 Brazil is the most dominant attacking nation in World Cup history
📉 Football became more defensive from the 1960s to 2000s
📈 Modern tournaments show a slight return to attacking football
🏟️ Home-listed advantage exists but is not a true home-field effect
🔥 Some matchups consistently generate high-scoring, entertaining games
# Visualizations Included
Goals per match over time (line chart)
Goals per decade comparison
Top attacking nations (bar charts)
Tournament entertainment ranking
Matchup scoring analysis

<img width="1595" height="776" alt="image" src="https://github.com/user-attachments/assets/ad88bf8a-7af8-4270-a675-1425be04bfb4" />

# Tech Stack
Python 🐍
Pandas
Matplotlib
NumPy
Data cleaning & transformation

Optional extensions:

Streamlit dashboard
Plotly interactive charts
# Project Structure
📦 fifa-world-cup-analytics
│
├── data/
│   └── clean_fifa_worldcup_historical_data.xlsx
│
├── notebooks/
│   └── analysis.ipynb
│
├── app/
│   └── streamlit_app.py
│
├── images/
│   └── charts.png
│
└── README.md
# Key Takeaway

Football is not just about winning — it evolves over time.

This analysis shows how the game has transformed:

From chaotic high-scoring football → to tactical defensive systems → to a modern balanced attacking era.

# Future Improvements
Build predictive model for match outcomes
Add expected goals (xG) simulation
Create interactive Streamlit dashboard
Include player-level World Cup analysis
Compare continental playing styles
# Author

Football Data Analytics Project
Built to explore football history using data science.

⭐ If you like this project

Star the repo ⭐ and explore more football analytics projects.
