# Global Internet Adoption Analysis

## Project Description

This project analyzes the growth of internet adoption worldwide using historical internet usage and population datasets.

The analysis combines data from multiple sources to calculate the percentage of the global population connected to the internet over time and identify key adoption milestones. Additionally, the project explores internet adoption in South America to determine when more than half of the region's population gained internet access.

---

## Table of Contents

- Business Understanding
- Data Understanding
- Screenshots of Results
- Technologies
- Setup
- Approach
- Key Findings
- Status
- Credits

---

## Business Understanding

Internet access has become an important part of communication, education, business, and everyday life. Understanding how internet adoption has evolved over time can help illustrate the growth of global connectivity.

The goal of this project was to analyze historical internet usage data and answer questions such as:

- When did the number of internet users exceed 100 million?
- What percentage of the world's population was connected to the internet each year?
- When did global internet adoption surpass 50% of the population?
- When did South America surpass 50% internet adoption?

---

## Data Understanding

This project uses four datasets:

### Global Analysis

- World Internet Users Dataset
- Historical World Population Dataset

### Continent Analysis

- Internet Users by Continent Dataset
- Historical Population by Continent Dataset

The datasets were merged using common year and continent fields to calculate internet adoption percentages.

---

## Screenshots of Results

### Global Internet Adoption Trend

<img width="642" height="493" alt="image" src="https://github.com/user-attachments/assets/1daa99cc-55b5-4050-9bae-6196edd33ae2" />


### Global Adoption Surpasses 50%

<img width="578" height="202" alt="image" src="https://github.com/user-attachments/assets/fbf41d70-1011-4c18-b02c-e01d3c141e6d" />


### South America Adoption Milestone

<img width="1061" height="180" alt="image" src="https://github.com/user-attachments/assets/3da4a087-51a0-4c89-8f40-c61ec5e55df5" />


---

## Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

### Skills Demonstrated

- Data Loading
- Data Cleaning
- Data Merging
- Exploratory Data Analysis (EDA)
- Data Visualization
- Data Transformation
- Data Querying with Pandas

---

## Setup

### Clone the Repository

```bash
git clone https://github.com/yourusername/global-internet-adoption-analysis.git
```

### Install Dependencies

```bash
pip install pandas matplotlib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Global Internet Adoption Analysis.ipynb
```

and run the cells sequentially.

---

## Approach

### 1. Data Loading

Loaded internet usage and population datasets into Pandas DataFrames.

### 2. Data Cleaning

Merged datasets using common fields and removed missing values using `dropna()`.

### 3. Feature Engineering

Calculated the percentage of the global population connected to the internet using:

```python
internet_users / population * 100
```

### 4. Exploratory Data Analysis

Answered the following questions:

- In what year did internet users exceed 100 million?
- What percentage of the world's population was connected to the internet each year?
- When did internet adoption exceed 50% globally?
- When did South America exceed 50% internet adoption?

### 5. Visualization

Created a line chart to visualize global internet adoption over time and identify the point at which internet usage surpassed 50% of the world's population.

---

## Key Findings

- Internet adoption increased dramatically between 1990 and 2022.
- Less than 0.1% of the world's population used the internet in 1990.
- More than 65% of the world's population was connected to the internet by 2022.
- Global internet adoption surpassed 50% in 2019.
- South America surpassed 50% internet adoption during the period analyzed.

---

## Status

**Status:** Complete

**Version:** 1.0

---

## Credits

### Learning Resources

- Cisco Data Science Essentials with Python
- Pandas Documentation
- Matplotlib Documentation

### Author

Juan Carlos Pascual
