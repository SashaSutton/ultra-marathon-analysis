# Ultra Marathon Data Analysis Project

## Overview
This project analyses ultra marathon data, specifically focusing on 50km and 50mi events held in the USA during 2020. The dataset includes details about races, athletes, and their performances. Using Python in Jupyter Notebook, the data is cleaned, processed, and visualised to uncover trends and insights about ultra marathon performance.

## Objectives
The key goals of this analysis are:
- To compare performance differences between male and female athletes.
- To identify the best and worst-performing age groups for ultra marathon races.
- To investigate seasonal variations in athlete speeds.

## Files in This Repository
ultra-marathon-analysis/
├── TWO_CENTURIES_OF_UM_RACES.csv   # Raw dataset from Kaggle
├── ultra_marathons_usa_50km_50mi_2020.ipynb   # Jupyter Notebook with analysis


### File Descriptions:
1. **TWO_CENTURIES_OF_UM_RACES.csv**:
   - The raw dataset downloaded from [Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running).
   - Contains information about ultra marathon events, including race distances, athlete demographics, and performance metrics.

2. **ultra_marathons_usa_50km_50mi_2020.ipynb**:
   - The Jupyter Notebook containing the full data analysis process:
     - Data cleaning: Filtering for relevant events, handling missing values, and standardising data.
     - Data visualisation: Exploring performance trends by age, gender, and season.

## Dataset
The dataset is sourced from Kaggle:  
[The Big Dataset of Ultra Marathon Running](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running).

## Installation
To run the notebook:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ultra-marathon-analysis.git
2. Install Python and the required libraries (if not already installed):
  . pandas
  . seaborn
3. Open the Jupyter Notebook:
  jupyter notebook ultra_marathons_usa_50km_50mi_2020.ipynb

## Key insights
1. Performance by gender
  Male athletes tend to have slightly faster average speeds for both 50km and 50mi races.
2. Best performing groups
  Athletes aged 30-40 perform best in 50mi races.
3. Seasonal variations
  Winter races exhibit faster average speeds compared to summer races.

## Acknowledgements
dataset: provided by aiaiaidavid on Kaggle.
tools used: Jupyter Notebook, pandas and seaborn.


   

