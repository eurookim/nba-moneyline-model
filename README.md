# NBA Moneyline Betting Model

## Overview
Statistical and machine learning analysis of whether pre-game betting market data
can predict NBA game outcomes.

## Key Findings
- Favorites win 68.4% of games — nearly identical in regular season vs. playoffs
- Home favorites win at 70.1% vs 64.7% for away favorites
- Model achieved 67.3% test accuracy

## Methods
- Engineered implied win probabilities and overround from raw American odds
- Logistic regression on pre-game features only
- 60/20/20 train/validation/test split across ~19,800 games

## Tech Stack
Python · pandas · scikit-learn · matplotlib · seaborn
