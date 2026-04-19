# Formula 1 Power Unit Performance Analysis (2022–2025)

A data-driven analytics project that evaluates Formula 1 power unit manufacturers during the Turbo Hybrid era (2022–2025) using advanced ranking methodologies.

## Project Overview

Most Formula 1 analysis focuses on drivers or constructors. This project shifts the focus to **power unit manufacturers**:

- Mercedes
- Ferrari
- Honda
- Renault

Since multiple teams use the same engine supplier, this creates an opportunity to analyse engine competitiveness across multiple teams and seasons.

## Objectives

- Collect and clean multi-season Formula 1 race data
- Map constructors to their power unit suppliers
- Analyse manufacturer performance trends
- Apply ranking models to compare competitiveness
- Visualise seasonal and long-term ranking evolution

## Ranking Models Used

### 1. Colley Matrix Method
A structured ranking system based on comparative outcomes.

Used for:
- Stable rankings
- Long-term consistency
- Unbiased comparisons

### 2. Exponential Decay Model
A weighted ranking model that gives stronger importance to higher and recent performances.

Used for:
- Momentum tracking
- Performance timing
- Recent competitiveness

## Dataset Sources

- Kaggle Formula 1 Dataset  
- FastF1 API

## Key Findings

- Honda was the strongest overall manufacturer across the analysed era.
- Mercedes showed strong consistency and late-era competitiveness.
- Ferrari performed strongly in equal-weight models.
- Renault remained lowest overall but showed occasional late-season improvements.
- Ranking outcomes depend heavily on the model used.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Output

The project includes:

- Data cleaning pipelines
- Ranking model implementations
- Seasonal comparisons
- Visualisations
- Final analytical report

## Future Improvements

- Hybrid ranking framework combining both models
- Include qualifying pace and reliability data
- Add weather / tyre strategy variables
- Predictive performance modelling

## Author

Ahmed Anuf
