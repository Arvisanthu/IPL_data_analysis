
## 🏏 **Project Title:** IPL Data Analysis

---

### 🎯 **1. Project Objectives**

* To perform a **comprehensive analysis of the Indian Premier League (IPL)** dataset to understand team and player performances over multiple seasons.
* To uncover insights such as:

  * Most successful teams and players.
  * Factors influencing match outcomes.
  * Venues and toss impacts.
  * Patterns in runs, wickets, and winning margins.
* To apply **data visualization and exploratory data analysis (EDA)** to reveal meaningful trends that could guide cricket analytics and strategy.

---

### ⚙️ **2. Methods**

1. **Data Loading & Cleaning**

   * Imported IPL datasets (e.g., *matches.csv* and *deliveries.csv*).
   * Checked for missing values, duplicates, and inconsistent data (e.g., team name formatting).
   * Renamed columns for clarity and filtered irrelevant features.

2. **Exploratory Data Analysis (EDA)**

   * Conducted summary statistics to understand overall match and player-level data.
   * Created dataframes to analyze match results, toss outcomes, and batting/bowling trends.

3. **Feature Engineering**

   * Derived new columns such as:

     * `win_by_runs`, `win_by_wickets`, `toss_decision`, and `venue`.
   * Calculated season-wise totals, averages, and win percentages.

4. **Visualization**

   * Used **Matplotlib**, **Seaborn**, and **Plotly** for visual representation:

     * Bar charts for most wins by team.
     * Pie charts for toss decision patterns.
     * Line graphs for season-wise performance trends.
     * Heatmaps for correlation between toss and match results.

5. **Performance Evaluation**

   * Ranked players and teams based on metrics such as:

     * Total matches played.
     * Number of wins.
     * Player of the Match awards.
     * Average runs and wickets.

---

### 🧾 **3. Datasets**

* **Files Used:**

  * `matches.csv` – Match-level data including season, teams, results, toss, and winners.
  * `deliveries.csv` – Ball-by-ball data including batsman, bowler, runs, and wickets.

* **Key Columns:**

  | Column                          | Description                 |
  | ------------------------------- | --------------------------- |
  | `id`                            | Unique match identifier     |
  | `season`                        | IPL season year             |
  | `city`                          | Venue city                  |
  | `date`                          | Match date                  |
  | `team1`, `team2`                | Competing teams             |
  | `toss_winner`, `toss_decision`  | Toss outcomes               |
  | `winner`                        | Match-winning team          |
  | `win_by_runs`, `win_by_wickets` | Winning margin metrics      |
  | `player_of_match`               | Best performer in the match |

* **Data Size:**

  * Matches: ~750 records
  * Deliveries: ~150,000 records (ball-by-ball)

---

### 📊 **4. Results**

#### **A. Team-Level Insights**

* **Mumbai Indians (MI)** emerged as the most successful franchise with the highest number of wins and titles.
* **Chennai Super Kings (CSK)** showed consistent performance with one of the best win percentages.
* **Royal Challengers Bangalore (RCB)** had high run-scoring games but lower win ratios compared to MI and CSK.

#### **B. Toss & Match Outcomes**

* Teams that **won the toss and chose to field** had a slightly higher probability of winning.
* **Toss-winning correlation with match outcome** ≈ 52–55%.

#### **C. Venue Analysis**

* Stadiums like **Eden Gardens (Kolkata)** and **Wankhede (Mumbai)** hosted the most matches.
* **Home advantage** played a significant role in wins (especially for MI and KKR).

#### **D. Player Performance**

* **Virat Kohli** and **David Warner** led in aggregate runs across seasons.
* **Lasith Malinga** and **Bhuvneshwar Kumar** topped wicket tallies.
* **Chris Gayle** recorded the highest number of centuries and sixes.

#### **E. Season Trends**

* Average total runs per match gradually increased till IPL 2018, showing the league’s evolving aggressive gameplay.
* Strike rates and boundary percentages saw upward trends season-over-season.

---

### 💡 **5. Insights**

1. **Toss Matters, but not Decisively**
   Winning the toss offers a small edge (around 5%) — especially in matches affected by dew or chasing advantage.

2. **Home Advantage Dominates**
   Teams perform significantly better at home venues, particularly in stadiums with short boundaries or crowd influence.

3. **Player Consistency Drives Success**
   Top-performing teams maintain a core group of consistent players (e.g., MI’s Rohit Sharma, CSK’s Dhoni).

4. **Batting Depth is Key**
   Teams with deep batting lineups (bat till No. 7 or 8) tend to win more closely contested matches.

5. **Evolution of the League**
   Data indicates that IPL has become increasingly batting-oriented, with more boundaries and higher average scores.

6. **Strategic Use Case**
   The findings can help franchises and analysts:

   * Optimize team composition based on conditions.
   * Make toss-based strategic decisions.
   * Predict match outcomes using data-driven probabilities.

---

### 🏁 **Conclusion**

This IPL Analysis project demonstrates how data science can uncover actionable insights in sports analytics.
By applying **EDA and visualization techniques**, the study:

* Identified dominant teams and consistent performers.
* Quantified the impact of toss and venue conditions.
* Highlighted the league’s evolution and gameplay trends.

It provides a foundation for **predictive modeling of match outcomes** and **performance-based decision-making** for franchises and analysts.

---

### **Data Visualisation:**

<img width="1104" height="360" alt="newplot (3)" src="https://github.com/user-attachments/assets/1d68ee26-ac65-4d70-8188-97744e76703a" />

<img width="1027" height="582" alt="toss decision" src="https://github.com/user-attachments/assets/8cfa8f6d-5349-4026-bdc5-81d93528eeda" />

<img width="1104" height="360" alt="newplot (4)" src="https://github.com/user-attachments/assets/d01af9d1-7c9a-44ce-9a72-318a69eca29c" />

<img width="1104" height="360" alt="newplot (5)" src="https://github.com/user-attachments/assets/11b94cec-93e0-40c5-88e2-b6bb74c8d53f" />

<img width="1104" height="360" alt="newplot (6)" src="https://github.com/user-attachments/assets/80cb4a52-12c7-493d-a7c7-9908b13cbdb2" />
