# Minor League Baseball Attendance Linear Regression Model

A data analysis and visualization comparing NCAA football operating success to on-field success from 2017-2022

---

## Overview

This was a poster presented at the 2nd Annual MSU Sports Analytics Conference 2026. After data filtering and initial exploratory data analysis, different predictors were tried for maximizing the adjusted R-squared value. Predictors range from baseball-oriented (win percentage, league), stadium-oriented (capacity, location), and geography-oriented (city population, density). Predictors were tested and altered accordingly to prevent covariance, until a final model was decided. Coefficient graphs and residual graphs were created, as well as a prediction model for hypothetical future locations. 

---

## Features

- Data cleaning
- Data visualization
- Multiple linear regression
- Feature engineering
- Prediction modeling
  
---


## Datasets

Source: The Baseball Cube - https://www.thebaseballcube.com/

Contains over 100 MiLB baseball team statistics from 2020-2024, including win and attendance statistics

Important variables:
- `team`
- `league`
- `level`
- `wpct`
- `attendance`
- `avg.game` (attendance)


Source: simplemaps - https://simplemaps.com/data/us-cities

Contains over 30000 US city statistics, including location (city/state/coordinates) and population (density, metro population)

Important variables:
- `city`
- `lat`, `long`
- `population`
- `density`
- `state_id`
---
