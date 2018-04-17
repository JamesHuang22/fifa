# What Makes the Best Defensive Footballers?

**Analyzing player attributes from FIFA '17 player rankings.**

Author: Brian Daisey

NOTE: View notebook online at https://bdaisey.github.io/fifa/

## Introduction

In football (soccer) as in most sports, the lion's share of the glory goes to the top offensive players.  This project shifts the focus onto the defensive element that actually wins championships.  


Using detailed player data from the FIFA '17 video game we will examine how defenders match up against the top 1000 players and one another.  Then we take a closer look at the defensive players by examining individual attributes and their contribution to the overall player ratings.  Hopefully after reading you will have a better idea of which skills are most crucial for the success of defensive footballers!

### Outline - Project is contained in Jupyter notebook in fifa_nb.ipynb

1. Getting Started
  - 1.1 Required Libraries
  - 1.2 Dataset Source
  - 1.3 Load and View Data
  - 1.4 Isolate Top 1000 Players
  - 1.5 Isolate Defenders
2. Explore Top 1000 Players
  - 2.1 Top 1000 Player Breakdown by Position 
  - 2.2 How Many Defenders in Top 1000?
3. Explore Defenders
  - 3.1 Defenders by Position
  - 3.2 Defenders by Rating
4. Begin Defender Analysis
  - 4.1 Selection of Attributes 
  - 4.2 Attributes vs. Rating, Visually
5. Reveal Key Attributes with Multiple Linear Regression
  - 5.1 Null Hypothesis
  - 5.2 Regression with scikit-learn
  - 5.3 Regression with statsmodels
6. Predict Rating From Attributes with Machine Learning
  - 6.1 Predictions with Train/Test Split
7. Conclusions
  - 7.1 Key Attributes
  - 7.2 Prediction of Overall Rating
