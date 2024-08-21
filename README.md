# Analysis of IPL Data using PySpark

Analyzing **IPL (Indian Premier League)** data and building a predictive model using **PySpark** and **Python**, cleaning and preprocessing the data, and performing feature engineering. This project aims to uncover performance patterns and provide valuable insights for team management and player selection.

## 📊🔍📝👉 For a detailed walkthrough of the PySpark EDA process and results, check out this [article](https://aishwaryahastak.medium.com/ipl-analysis-using-pyspark-478a53ce9c98).

# Introduction

The **IPL (Indian Premier League)** cricket data analysis project aims to uncover performance patterns and insights at both the player and team levels. Through refining **data types**, resolving **inconsistencies**, and performing **feature engineering**, this project seeks to deepen the understanding of factors influencing match outcomes and player performances.

Utilizing **PySpark** in **Databricks**, the dataset has been transformed and enriched by creating new fields such as **partnership runs**, enhancing the analysis. Created visualizations using **Python** libraries like **matplotlib** and **seaborn**.

The insights gained from this analysis are expected to be valuable for developing strategies in **team management**, **player selection**, and **game planning**, contributing to a data-driven approach in the IPL. This could also benefit cricket enthusiasts in building their ideal teams.

# 💻 Technical Tools Used:

- **ETL Processes**: Extract, Transform, Load methodologies
- **Transformation Functions**: `select`, `filter`, `groupBy`, `withColumn`, `selectExpr`
- **Aggregation Functions**: `count`, `sum`, `avg`, and more
- **Pivot Tables**
- **Window Functions**: Functions such as `rank()`, `dense_rank()`, and `lag()`
- **Visualization Libraries**: `matplotlib`, `seaborn` 

# 🎯 Key Objectives:

- Analyze **IPL cricket data** to uncover performance patterns and insights at both player and team levels.
- Refine and enrich the dataset through advanced **feature engineering** and **transformation functions** to improve prediction accuracy. 
- Provide actionable insights for **team management**, **player selection**, and strategic **game planning**.

# 🔍 Key Insights:

- **Top IPL Players with Most 'Player of the Match' Awards**: AB de Villiers leads with the highest number of 'Player of the Match' awards, showcasing his exceptional performance.
  
- **Performance Analysis of Top Batsmen Across IPL Overs**: CH Gayle displays solid performance throughout but particularly shines in the middle overs, indicating a steady scoring rate.

- **Bowlers vs. Batsmen: Uncovering the Toughest Matchups in IPL**: Sunil Narine has dismissed Rohit Sharma the most times (9 wickets).

- **IPL Teams' Performance Based on Toss Decisions and First Innings Batting**: Mumbai Indians, Kolkata Knight Riders, and Rajasthan Royals have high win percentages when batting first, indicating strong performance when leading.

- **Top IPL Bowlers: Total Wickets and Average Wickets Per Match**: Lasith Malinga and Jasprit Bumrah are standout bowlers with the highest average wickets per match, each taking approximately 2 wickets per game.

- **Patterns in Dismissal Types and Match Situations**:

    - **"Caught"** is the most common dismissal type, especially in league matches.
    
    - **"Run out"** dismissals occur later in high-stakes matches like finals and eliminators, reflecting increased risk-taking in crucial moments.
    
    - Early wickets in qualifiers and finals are often due to **"bowled"** and **"LBW"** dismissals, highlighting effective bowling strategies in key games.
