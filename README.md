# Animal-Shelter-Data-Analysis
## Factors Influencing Adoption vs Euthanasia

## Description
The study of Factors Influencing Adoption vs Euthanasia in Animal Shelters delves into the multifaceted dynamics that contribute to the outcomes of animal shelter residents. By meticulously examining a range of variables and their interplay, this analysis aims to unravel the determinants that steer the choices between adoption and euthanasia for sheltered animals. Through rigorous exploration and data-driven insights, this investigation sheds light on the intricate factors that influence the ultimate destiny of these animals within the shelter environment.


## Objective
The primary objective of this analysis is to gain comprehensive insights into the diverse factors that play a pivotal role in shaping the outcomes of animals in shelters, specifically focusing on the critical dichotomy between adoption and euthanasia. By leveraging data analysis techniques, including visualization, machine learning, and potentially linear optimization, we aim to uncover patterns, correlations, and trends that empower informed decision-making within the realm of animal shelter management. Ultimately, this analysis seeks to provide actionable recommendations and strategies that can contribute to enhancing adoption rates while minimizing euthanasia occurrences, thereby fostering improved animal welfare and shelter efficacy.

## Data Pipeline

### Data Preparation and Cleaning:
- Loaded raw data files using Pandas.
- Conducted initial analysis of features to identify issues like missing or incorrect values.
- Performed data cleaning to address issues in the dataset.

### Exploratory Data Analysis and Visualization:
1. Analyzed key features to understand their distributions and relationships:
- Animal Type
- Sex Upon Intake
- Age at Intake
- Intake Condition
- Intake Type
2. Utilized visualizations to gain insights into the data.

### Feature Engineering:
Created new features to enhance model predictive power, including:
- Exploration of Duration of Stay and its impact on Adoption and Euthanasia outcomes.

### Data Preprocessing:
- Imputed missing values in numerical columns using median values.
- Applied one-hot encoding to categorical columns to transform them into numerical features.
- Created binary feature 'NamePresent' based on the presence of names.
- Dropped 'Name' and 'Animal ID' columns.
- Performed feature scaling using StandardScaler on selected numerical columns.

### Model Building:
Constructed the predictive model:
- Selected appropriate features for training and testing.
- Chose a machine learning algorithm suitable for the prediction task.
- Split data into training and testing sets.
- Trained and evaluated the model's performance.
