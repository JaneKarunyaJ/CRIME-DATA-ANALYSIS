# Crime Data Analysis in Tamil Nadu (2014–Present)

This project presents an in-depth analysis of crime data in Tamil Nadu from 2014 to the present. It utilizes data science techniques to uncover patterns, trends, and correlations to assist in effective crime prevention and resource planning.

---

## Problem Statement

Crime data from Tamil Nadu remains largely under-analyzed. There is a lack of structured insight into crime trends, victim demographics, police deployment, and case resolution. This project aims to bridge these gaps with data-driven insights for policy formulation and law enforcement optimization.

---

## Objectives

- Analyze temporal crime trends across districts
- Identify peak crime hours and high-risk zones
- Classify crimes based on their nature and severity
- Explore police deployment patterns and case closure rates
- Investigate demographic patterns in victimization
- Recommend data-informed crime prevention strategies

---

## Dataset Overview

| Feature             | Description                          |
|---------------------|--------------------------------------|
| Date of Occurrence  | When the crime occurred              |
| City                | Location of the incident             |
| Crime Description   | Type of crime                        |
| Victim Age & Gender | Demographic data of the victim       |
| Weapon Used         | Weapon involved, if any              |
| Crime Domain        | Category (Violent/Other)             |
| Police Deployed     | Number of officers deployed          |
| Case Closed         | Whether the case was resolved        |
| Date Case Closed    | When the case was closed             |

> Data used: `CRIME.csv` (originally from 2014–Present)

---

## Tools & Technologies

- **Python**: Data processing and analysis
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn, Plotly**: Data visualization
- **scikit-learn**: Label Encoding
- **Google Colab**: Development environment

---

## Key Insights

- **Peak Crime Time**: Most incidents happen between 1 AM – 6 AM.
- **Urban Crime Hotspots**: Chennai has the highest number of reported crimes.
- **Irregular Police Deployment**: Many high-severity crimes lack sufficient enforcement.
- **Low Closure Rates**: Less than 50% of cases are closed.
- **Victim Demographics**: Individuals aged 30–50, particularly women, are more frequently targeted.

---

## Visualizations

- Daily crime trends with rolling average
- Crime domain distribution bar chart
- Top 10 crime types in Tamil Nadu
- Heatmap of crime by hour and day
- Scatter plots of:
  - Victim Age vs Police Deployment
  - Police Deployment vs Case Closure Duration


