# 🏟️ Home Advantage Analysis

This project investigates the enduring yet elusive concept of home-field advantage in professional football. By exploring performance metrics across leagues, teams, seasons, and competitive contexts—including referee behavior and COVID-era disruptions—this study reveals how home advantage evolves, fluctuates, and responds to broader structural forces.

## 🧭 Objectives
- Quantify home win and undefeated rates across countries and leagues
- Examine performance differentials in attacking and defensive metrics by venue
- Analyze the role of team strength using Elo ratings
- Assess changes in home advantage during COVID-19 restrictions
- Explore the influence of referee behavior across different match environments

## 📁 Data Sources
- 📊 [Club Football Match Data (2000–2025)](https://www.kaggle.com/datasets/adamgbor/club-football-match-data-2000-2025) from Kaggle  
- ⚔️ Historical match results from [Football-Data.co.uk](https://www.football-data.co.uk/)  
- ♟️ Elo ratings from [ClubElo](http://clubelo.com/)

## 🧪 Methodology
- Preprocessing and normalization using `tidyverse`, `lubridate`, and `stringr`
- Visualizations built with `ggplot2` and conditional formatting using `kableExtra`
- Principal Component Analysis (PCA) and comparative diagnostics
- Map visualizations using `rnaturalearth` and spatial joins
- Behavioral analysis of foul and card distributions across leagues and time periods

## 🔍 Key Findings
- 🟩 Home teams consistently outperform away sides across major metrics
- 🌍 Home advantage varies significantly across countries and tactical cultures
- 🧠 Elo-based modeling shows stronger teams dilute venue effects
- 👥 Crowd absence during COVID-19 reduced home advantage measurably
- ⚖️ Referees are influenced by crowd pressure—penalizing away teams more, especially pre-COVID

## 📄 R Scripts & Markdown Files
If you'd like to explore the full analytical workflow—including the R scripts, markdown logic, and preprocessing steps used in this study—you can view the source file:

🔗 [View the full analysis](https://github.com/mbaffico/global-football-analysis/tree/main/home-advantage-analysis)
