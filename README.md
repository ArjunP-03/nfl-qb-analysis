# NFL Quarterback Performance Analysis (2004–2016)

This repository explores NFL quarterback performance over the 2004–2016 seasons using historical game and season statistics. Through data analysis and visualizations, we highlight trends in key quarterback metrics, examine dominant QB performances, and dive into historic seasons.

## Overview

The analysis is organized into several sections:

1. **QB Trends Over Time (2004–2016)**  
   - Examines metrics such as passing attempts, completions, touchdowns, interceptions, and passer rating.  
   - Visualizations show how quarterback performance has evolved over the years.

2. **Dominant Quarterbacks of the 2011 Season**  
   - Focuses on standout QBs like Aaron Rodgers, Drew Brees, Tom Brady, and Matthew Stafford.  
   - Game-by-game analysis compares individual performance to the league average.  
   - Highlights consistency and exceptional performances throughout the season.

3. **Peyton Manning’s Historic 2013 Season**  
   - Analyzes Manning’s efficiency using metrics such as yards per attempt (YPA) and touchdowns per attempt (TD/Att).  
   - Scatterplots compare all quarterbacks, highlighting Manning’s exceptional combination of volume and efficiency.  
   - Outliers are identified to focus on meaningful performance comparisons.

## Data

- The dataset consists of QB statistics for each season from 2004 to 2016.  
- Columns include: `qb`, `att` (pass attempts), `cmp` (completions), `yds` (yards), `ypa` (yards per attempt), `td` (touchdowns), `int` (interceptions), `lg` (longest pass), `sack`, `loss`, `rate` (passer rating), `game_points`, `home_away`, and `year`.

## Tools & Libraries

- **Python 3**
- **Pandas** for data manipulation
- **SQLite** for storing and querying data
- **Matplotlib** and **Seaborn** for visualizations
