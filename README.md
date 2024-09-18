# HR Data Analysis

This repository contains an analysis of HR-related data aimed at exploring various factors that influence employee promotion, performance, and overall HR metrics. The data analysis covers aspects such as employee demographics, department performance, and key performance indicators (KPIs).

## Overview

The Jupyter Notebook in this repository walks through the following steps:
1. **Importing necessary packages**: Libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn` are used for data manipulation, visualization, and analysis.
2. **Reading the dataset**: The dataset is loaded and explored using `pandas`. It contains information about employees, such as their department, education, performance ratings, and promotion status.
3. **Checking for missing values**: The notebook checks for missing or incomplete data to ensure clean and reliable analysis.
4. **Data Cleaning and Preprocessing**: The dataset is prepared for analysis by handling missing values and transforming relevant columns.
5. **Exploratory Data Analysis (EDA)**: Various visualizations and statistical methods are applied to uncover insights related to:
   - Employee demographics
   - Departmental performance
   - Training effectiveness
   - Promotion likelihood
6. **Key Metrics Analyzed**:
   - `KPIs_met >80%`
   - `Awards_won?`
   - `Previous_year_rating`
   - `Avg_training_score`
7. **Predictive Analysis**: Machine learning models can be used to predict employee promotion based on the provided features.

## Dataset

The dataset consists of the following columns:
- `employee_id`: Unique identifier for each employee
- `department`: Department in which the employee works
- `region`: Geographical region of the employee
- `education`: Educational background of the employee
- `gender`: Gender of the employee
- `recruitment_channel`: The channel through which the employee was hired
- `no_of_trainings`: Number of trainings completed by the employee
- `age`: Age of the employee
- `previous_year_rating`: Employee's performance rating for the previous year
- `length_of_service`: Number of years the employee has been with the company
- `KPIs_met >80%`: Whether the employee met more than 80% of their KPIs
- `awards_won?`: Whether the employee has won any awards
- `avg_training_score`: Average score in employee trainings
- `is_promoted`: Whether the employee was promoted

## Getting Started

### Prerequisites

To run the analysis, ensure that you have the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install them via pip:

```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/tarunramavath/HR-data-analysis.git
   ```
2. Navigate to the folder:
   ```bash
   cd HR-data-analysis
   ```
3. Launch Jupyter Notebook and open the `hr_dataset.ipynb` file:
   ```bash
   jupyter notebook
   ```

## Future Work

- **Feature Engineering**: Extracting more meaningful features from the dataset for better analysis and predictive modeling.
- **Machine Learning**: Building models to predict employee promotion.
- **Visualization Enhancements**: Creating interactive dashboards for better insights.
