# Chess Player Skill Classification using Machine Learning

This project explores the application of **machine learning** to classify chess players based on their skill levels, inferred from their game records. The analysis uses large-scale chess datasets collected from [Lichess](https://database.lichess.org), focusing on classical games with Stockfish evaluations.  

## Project Overview

The project consists of two main stages:

### 1. Initial Data Exploration (First Stage)
- Parsing raw `.pgn` files into structured `.csv` datasets.  
- Performing basic preprocessing, visualizations, and preliminary analysis.  
- Testing initial ML models to explore the feasibility of player classification.  
- This stage was crucial for understanding the dataset and preparing features for the final analysis.

### 2. Advanced Analysis and Player Classification (Final Stage)
- Preprocessing and merging large datasets to create a cleaned dataframe of ~11,000 classical games.  
- Conducting exploratory data analysis and feature engineering, including:  
  - Game length, move evaluations, and timing patterns  
  - Opening categories (ECO classification)  
  - Player rating categories (from Novice to Expert)  
- Testing hypotheses about player behavior and game dynamics.  
- Building ML models to classify players according to their skill level based on game characteristics.

## Datasets
- The raw and intermediate datasets are large and available separately on [Yandex Disk](https://disk.yandex.com/d/EGHi7eWtsn3Vvw).  
