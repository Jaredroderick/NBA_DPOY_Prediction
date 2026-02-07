# NBA Defensive Player of the Year Prediction Model

## Overview
This project implements an extreme gradient boosting (XGBoost) regression model to predict final voting share for the NBA Defensive Player of the Year (DPOY) award.

The model uses player and team data beginning with the 2013–14 NBA season, when the league began prioritizing player tracking data.

## Methodology
The modeling pipeline iteratively trains, evaluates, and refines predictive models to improve performance. Final predictions are ranked by projected voting share.

To reflect real-world award eligibility, results are filtered to include only players on pace to:
- Play at least 65 games
- Average at least 20 minutes per game

## Output
The final output is a ranked list of DPOY candidates based on predicted voting share.

## Video Explanation
The link below will provide you with my brief video explanation presenting this project. https://youtu.be/DGDMw5bNJwc