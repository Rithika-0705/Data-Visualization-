# Ocean Plastic Pollution Analysis
### Data Visualization Techniques Lab

This project analyzes the **Ocean Plastic Pollution Dataset** using Python-based data processing, exploratory data analysis (EDA), preprocessing techniques, statistical analysis, data visualization, calculated fields, grouping and aggregation, and correlation analysis.

---

## Dataset

**Dataset:** Plastic Pollution Dataset  
**Source:** [Kaggle — Plastic Pollution Dataset](https://www.kaggle.com/datasets/imtkaggleteam/plastic-pollution)

The dataset contains information related to plastic pollution and plastic waste entering the ocean from different countries and regions.

The dataset includes attributes such as:

- Entity
- Country Code
- Year
- Share of Global Plastics Emitted to Ocean
- Mismanaged Plastic Waste Per Capita

The project analyzes the distribution of plastic pollution, identifies major contributors to ocean plastic pollution, and studies the relationship between mismanaged plastic waste and plastic entering the ocean.

---

## Project Objective

The objective of this project is to analyze the Ocean Plastic Pollution dataset, perform data preprocessing, explore pollution-related patterns, calculate statistical measures, apply data grouping and correlation analysis, create calculated fields, and represent the results through suitable visualizations.

The project demonstrates how data analysis and visualization techniques can be used to understand:

- Ocean plastic pollution distribution
- Major contributors to ocean plastic pollution
- Mismanaged plastic waste
- Pollution-level categories
- Pollution patterns across entities
- Statistical characteristics of plastic pollution
- Relationships between numerical pollution variables
- Distribution of low, moderate, and high pollution categories
- Relationship between mismanaged plastic waste and ocean plastic pollution

---

## Experiments

### Experiment 1 — Ocean Plastic Pollution Analysis

**Aim:**
To analyze the Ocean Plastic Pollution dataset using Exploratory Data Analysis (EDA), visualize important pollution patterns, perform statistical analysis, and understand major contributors to ocean plastic pollution.

**Work Performed:**
- Dataset loading and inspection
- Dataset shape and information analysis
- Missing-value detection
- Data preprocessing
- Ocean plastic pollution visualization
- Analysis of major pollution contributors
- Numerical and categorical data analysis
- Statistical analysis
- Data visualization
- Export of processed data to Excel

**Outcome:**
The Ocean Plastic Pollution dataset was successfully loaded, analyzed, and visualized. The analysis provided insights into the distribution of plastic pollution and helped identify entities contributing significantly to ocean plastic pollution.

---

### Experiment 2 — EDA – Data Cleaning

**Aim:**
To clean the Ocean Plastic Pollution dataset by detecting and handling missing values, removing duplicate records, checking data types, and normalizing numerical data.

**Work Performed:**
- Identification of missing values
- Handling missing numerical values
- Duplicate-record detection
- Removal of duplicate records
- Inspection of data types
- Min-Max Scaling
- Standardization using StandardScaler
- Display of cleaned and normalized data

**Outcome:**
The dataset was successfully cleaned and numerical features were processed using Min-Max Scaling and Standardization, preparing the dataset for further analysis and visualization.

---

### Experiment 3 — EDA – Data Inspection and Analysis

**Aim:**
To inspect and analyze the Ocean Plastic Pollution dataset using DataFrame operations, conditional filtering, descriptive statistics, and measures of central tendency and dispersion.

**Work Performed:**
- Viewing the first five records
- Viewing the last five records
- Inspecting dataset shape
- Inspecting column names
- Checking data types
- Filtering entities based on ocean plastic pollution
- Filtering entities with high pollution contributions
- Selecting specific columns
- Calculating mean
- Calculating median
- Calculating mode
- Calculating range
- Calculating variance
- Calculating standard deviation
- Generating descriptive statistics

**Outcome:**
The experiment provides statistical insights into the numerical features of the Ocean Plastic Pollution dataset, particularly the share of global plastics emitted into the ocean and mismanaged plastic waste per capita.

---

### Experiment 4 — Data Visualization

**Aim:**
To visualize the Ocean Plastic Pollution dataset using Python by creating bar charts, pie charts, and line charts for better understanding of pollution patterns.

**Visualizations:**
- **Bar Chart:** Ocean plastic pollution by entity
- **Pie Chart:** Distribution of pollution contribution
- **Line Chart:** Plastic pollution across entities or years

**Outcome:**
The visualizations provide an intuitive understanding of ocean plastic pollution distribution, major contributing entities, and pollution patterns within the dataset.

---

### Experiment 5 — Calculated Field and Data Visualization

**Aim:**
To analyze the Ocean Plastic Pollution dataset using Python by creating a calculated field and basic visualizations such as bar charts, line charts, and pie charts.

**Work Performed:**

A calculated field named **Pollution Level** was created based on the share of global plastics emitted into the ocean.

The pollution levels are classified as:

- Low Pollution
- Moderate Pollution
- High Pollution

**Classification:**

- Less than 1% → Low Pollution
- 1% to 5% → Moderate Pollution
- Greater than 5% → High Pollution

**Visualizations:**
- **Bar Chart:** Number of entities by pollution level
- **Line Chart:** Ocean plastic pollution by entity
- **Pie Chart:** Distribution of pollution levels

**Outcome:**
The calculated field and visualizations provide a clearer understanding of pollution-level categories and help identify entities with comparatively high contributions to ocean plastic pollution.

---

### Experiment 6 — EDA – Grouping and Aggregation

**Aim:**
To perform grouping and aggregation on the Ocean Plastic Pollution dataset using Pandas and analyze pollution characteristics based on different pollution-level categories.

**Work Performed:**
- Grouping entities based on pollution level
- Calculation of total entities in each pollution category
- Calculation of average pollution contribution
- Calculation of maximum pollution contribution
- Identification of top entities
- Comparison of pollution categories
- Bar-chart visualization of pollution categories
- Analysis of average pollution by category

**Outcome:**
The grouping and aggregation analysis identifies differences in the number of entities, average pollution contribution, and maximum pollution contribution across Low, Moderate, and High pollution categories.

---

### Experiment 7 — EDA – Correlation Analysis

**Aim:**
To analyze the relationship between numerical variables in the Ocean Plastic Pollution dataset using correlation analysis and a heatmap.

**Work Performed:**

The following numerical attributes were analyzed:

- Year
- Share of Global Plastics Emitted to Ocean
- Mismanaged Plastic Waste Per Capita

A correlation matrix was calculated and visualized using a heatmap.

**Visualization:** Correlation Heatmap

**Outcome:**
The correlation analysis provides an understanding of the relationships between numerical pollution variables and helps identify the strength and direction of relationships between mismanaged plastic waste and ocean plastic pollution.

---

## How This Project Aligns with Data Visualization

### 1. Comparison

Bar charts are used to compare:

- Ocean plastic pollution across entities
- Number of entities across pollution categories
- Average pollution contribution across different categories

### 2. Trends

Line charts are used to visualize:

- Changes in plastic pollution across entities
- Pollution patterns across available years

### 3. Distribution

Pie charts are used to represent:

- Distribution of pollution levels
- Relative contribution of entities to ocean plastic pollution

### 4. Relationships

The project uses visualizations to study relationships such as:

- Mismanaged plastic waste vs ocean plastic pollution
- Entity vs pollution contribution
- Pollution level vs number of entities

### 5. Correlation

A correlation heatmap is used to show relationships between numerical variables such as:

- Year
- Share of global plastics emitted to ocean
- Mismanaged plastic waste per capita

### 6. Statistical Analysis

Mean, median, mode, range, variance, standard deviation, and descriptive statistics are used to understand numerical pollution data.

### 7. Multivariate Analysis

Multiple pollution-related attributes are analyzed together to understand patterns associated with ocean plastic pollution and mismanaged plastic waste.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab
- Excel
- GitHub

---

## Data Analysis

The project focuses on Exploratory Data Analysis and visualization of ocean plastic pollution.

**Techniques Used:**

- Data Cleaning
- Data Inspection
- Data Transformation
- Calculated Fields
- Statistical Analysis
- Grouping and Aggregation
- Correlation Analysis
- Data Visualization

---

## Dataset Information

The original Kaggle Plastic Pollution dataset contains information related to plastic waste and pollution across different entities.

The project uses datasets containing information about the **share of global plastics emitted into the ocean** and **mismanaged plastic waste per capita**.

### Attributes

| Attribute | Description |
|---|---|
| Entity | Country or region represented in the dataset |
| Code | Country or region code |
| Year | Year associated with the observation |
| Share of global plastics emitted to ocean | Percentage share of global plastics emitted into the ocean |
| Mismanaged plastic waste per capita | Amount of mismanaged plastic waste per person per year |

*These attribute definitions follow the dataset's Kaggle documentation.*

---

## Project Structure
https://github.com/Rithika-0705/Data-Visualization-/new/main?filename=README.md

