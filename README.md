# Students' Mental Health – Exploratory Data Analysis (EDA)

This project investigates the impact of academic background, environment, and personal context on students' mental health. By analyzing key mental health indicators—depression, anxiety, isolation, and future insecurity—the study aims to uncover patterns and highlight groups that may require additional support or targeted interventions.

## Table of Contents

- Project Overview  
- Dataset Description  
- Methodology  
- Results and Visualizations  
- Key Insights  
- How to Use  
- Contributing  
- License  

## Project Overview

This exploratory data analysis focuses on understanding how students' mental health varies across different academic demographics. The primary objective is to identify potential risk groups and trends using descriptive statistics and visual tools.

We analyze the dataset using groupings such as:

- Degree Level (e.g., Undergraduate, Postgraduate)
- Degree Major (e.g., Engineering, Humanities, Social Sciences)

Mental health metrics are evaluated using aggregated statistics (mean, sum, min, max) for each category.

## Dataset Description

The dataset includes the following fields:

- `degree_level`: Academic standing of the student
- `degree_major`: Field of study
- `depression`: Self-reported level of depression
- `anxiety`: Self-reported level of anxiety
- `isolation`: Level of social isolation
- `future_insecurity`: Concerns about future security or stability

Each record corresponds to a student and contains anonymized data to protect identity.

## Methodology

- Cleaned and standardized the dataset for consistency
- Grouped data based on academic categories
- Computed summary statistics for each mental health metric
- Used heatmaps and bar plots to visualize comparative trends
- Focused on highlighting areas of concern for certain groups

## Results and Visualizations

The project includes several visualizations such as:

- Heatmaps of average depression, anxiety, and isolation scores by major and degree level
- Comparative bar charts to contrast mental health conditions between different academic groups

These visualizations help pinpoint demographic areas with consistently higher mental health concerns.

## Key Insights

- Certain majors show a higher average of depression and anxiety compared to others
- Postgraduate students tend to report higher future insecurity than undergraduates
- Isolation levels vary significantly between academic disciplines, suggesting the importance of community factors

These findings can be useful for campus counselors, education policymakers, and student support organizations.

## How to Use

To explore or reproduce this project:

1. Clone the repository  
2. Open the Jupyter Notebook file  
3. Run all cells to see the analysis and visualizations  

Python libraries used include:
- `pandas`
- `seaborn`
- `matplotlib`

## Contributing

Contributions are welcome. To contribute:

- Fork the repository  
- Create a new branch for your feature or fix  
- Submit a pull request for review  

Please ensure that your changes are well-documented and consistent with the existing structure.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project with attribution.

