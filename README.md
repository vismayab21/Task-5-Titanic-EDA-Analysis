
# Titanic Dataset – Exploratory Data Analysis (EDA)

##  Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The aim is to understand the dataset, identify patterns, explore relationships between variables, and discover factors that influenced passenger survival.

##  Objectives

- Understand the Titanic dataset.
- Explore and analyze data using Pandas.
- Identify and handle missing values.
- Analyze data distributions and relationships.
- Create visualizations using Matplotlib and Seaborn.
- Extract meaningful insights from the dataset.

##  Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

##  Dataset

The Titanic dataset contains passenger information such as:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Ticket information
- Fare
- Embarkation details

##  Exploratory Data Analysis

### 1. Data Understanding

- Displayed the first few rows using `head()`.
- Checked the dataset shape and column names.
- Used `info()` to understand data types.
- Used `describe()` to view statistical summaries.

### 2. Data Cleaning

- Checked for missing values.
- Identified duplicate records.
- Filled missing age values using the median.
- Filled missing embarkation values using the mode.
- Created a cleaned copy of the dataset.

### 3. Statistical Analysis

- Used `value_counts()` to analyze passenger categories.
- Examined passenger survival counts.
- Calculated statistical summaries.
- Checked skewness in numerical columns.

### 4. Data Visualization

The following visualizations were created using Matplotlib and Seaborn.

#### Survival Count

This graph shows the number of passengers who survived and did not survive.

![Survival Count](Screenshots/survival_count.png)

#### Correlation Heatmap

This heatmap shows the correlation between numerical features in the dataset.

![Correlation Heatmap](Screenshots/correlation_heatmap.png)

#### Age Distribution

This histogram shows the distribution of passenger ages.

![Age Distribution](Screenshots/age_distribution.png)

##  Key Findings

- The dataset contains information about Titanic passengers.
- Survival rates differed between male and female passengers.
- Passenger class was related to survival chances.
- Most passengers were adults.
- Age and fare showed different distribution patterns.
- Correlation analysis helped identify relationships between numerical variables.

##  Project Folder Structure

```text
Titanic-EDA-Analysis/
│
├── Dataset/
│   └── titanic_cleaned.csv
│
├── Notebook/
│   └── Titanic_EDA_Analysis.ipynb
│
├── Report/
│   └── Titanic_EDA_Report.pdf
│
├── Screenshots/
│   ├── survival_count.png
│   ├── correlation_heatmap.png
│   └── age_distribution.png
│
└── README.md
```

##  How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open the `Titanic_EDA_Analysis.ipynb` notebook in Google Colab or Jupyter Notebook.
4. Run the notebook cells one by one.
5. Explore the analysis and visualizations.

##  Skills Gained

- Exploratory Data Analysis
- Data Cleaning
- Statistical Analysis
- Data Visualization
- Python Programming
- Data Interpretation

##  Conclusion

This project provided practical experience in Exploratory Data Analysis using Python. The Titanic dataset was explored, missing values were handled, statistical analysis was performed, and visualizations were created to understand passenger data and survival patterns.

---

**Task 5: Exploratory Data Analysis (EDA)**  
**Project: Titanic Dataset Analysis**
