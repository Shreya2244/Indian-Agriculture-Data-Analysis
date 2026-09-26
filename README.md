# Indian Agriculture Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA) on Indian agricultural data** using Python. The analysis focuses on crop-wise, state-wise, district-wise, and year-wise patterns in **cultivated area, production, and yield**.

The project uses the **ICRISAT District-Level Agriculture Dataset** and applies Python-based data cleaning, statistical analysis, correlation analysis, and visualization to convert raw agricultural data into meaningful insights.

---

## 🎯 Objectives

- Analyze Indian agricultural data using Python.
- Understand crop-wise area, production, and yield patterns.
- Identify year-wise production trends.
- Compare agricultural performance across states and districts.
- Study relationships between cultivated area, production, and yield.
- Identify variations and outliers in agricultural data.
- Create meaningful visualizations to communicate findings.
- Extract practical insights from the dataset through EDA.

---

## 📂 Dataset

**Source:** ICRISAT (International Crops Research Institute for the Semi-Arid Tropics)

The dataset contains district-level yearly agricultural information, including:

- Crop-wise area — **1000 hectares**
- Production — **1000 tonnes**
- Yield — **kg/ha**
- Data across multiple districts and years
- Information covering major crops

### Dataset File

```text
ICRISAT-District Level Data.csv
```

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- **Pandas** — data loading, cleaning, manipulation, and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization

### Environment
- Jupyter Notebook

> This version of the project focuses on **Python-based EDA**.

---

## 🔍 EDA Workflow

The project follows the following workflow:

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Missing Value Analysis
     ↓
Statistical Analysis
     ↓
Univariate Analysis
     ↓
Bivariate Analysis
     ↓
Multivariate Analysis
     ↓
Correlation Analysis
     ↓
Trend Analysis
     ↓
State / Crop Comparisons
     ↓
Visualization
     ↓
Key Insights
```

---

## 📊 Analysis Performed

### 1. Data Cleaning

- Loaded the ICRISAT dataset using Pandas.
- Inspected the structure and data types.
- Checked for missing values.
- Examined duplicate records.
- Prepared the dataset for analysis.

### 2. Statistical Analysis

Used descriptive statistics to understand:

- Mean
- Median
- Minimum
- Maximum
- Standard deviation
- Data distributions

### 3. Crop Area Analysis

Compared the cultivated area of major crops to understand which crops occupy larger agricultural areas.

### 4. Production Trend Analysis

Analyzed yearly production trends for major crops such as:

- Rice
- Wheat
- Pulses
- Oilseeds

### 5. State-wise Analysis

Compared agricultural production and yield across states to identify regional differences.

### 6. Yield Analysis

Examined yield distributions and variations across crops and regions.

### 7. Correlation Analysis

Used correlation analysis and heatmaps to study relationships between agricultural variables.

For example, the analysis found a **0.21 correlation between Kharif Sorghum Area and Rabi Sorghum Area**, indicating a weak positive relationship.

### 8. Area vs Production Analysis

Scatter plots were used to examine the relationship between cultivated area and production.

### 9. Crop Diversity Analysis

Compared the number of crops represented across states to understand differences in crop diversity.

---

## 📈 Visualizations

The project includes several visualization techniques:

- Bar charts
- Line charts
- Pie charts
- Box plots
- Scatter plots
- Correlation heatmaps
- Trend visualizations

### Examples of Analysis

#### Crop Area Distribution
Used to compare the agricultural area allocated to major crops.

#### Yearly Rice Production
Used to examine production trends over time.

#### State-wise Wheat Production
Used to compare wheat production across states.

#### Sorghum Yield Distribution
A box plot was used to examine yield variation and identify potential outliers.

#### Vegetable Area Distribution
Used to compare vegetable cultivation areas across states.

#### Chickpea Area vs Production
A scatter plot was used to examine the relationship between cultivated area and production.

#### Crop Diversity by State
Used to compare the variety of crops represented across states.

---

## 💡 Key Insights

### 🌾 Crop Area Distribution

Rice, wheat, and maize account for a substantial amount of the analyzed agricultural area, highlighting their importance within the dataset.

### 🌾 Rice Production

The highest rice production in the analysis was recorded in **2016**, at approximately **117,614.1 thousand tonnes**.

### 🌾 Wheat Production

**Uttar Pradesh** recorded the highest wheat production in the analysis, while **Kerala** recorded the lowest among the states represented.

### 🌱 Sorghum Yield

The reported average sorghum yield was approximately **586.09 kg/ha**, with variation across states and seasons.

### 🥬 Vegetable Cultivation

**Odisha** had the largest vegetable cultivation area in the analysis, followed by West Bengal and Uttar Pradesh.

### 📈 Chickpea Area vs Production

The analysis showed a strong positive relationship between chickpea cultivated area and production. Some observations deviated from the general trend, indicating that production is not always directly proportional to cultivated area.

### 🌱 Crop Diversity

Maharashtra, Madhya Pradesh, and Punjab showed high crop variety in the analyzed dataset.

---

## 📁 Project Structure

```text
Indian-Agriculture-Data-Analysis/
│
├── ICRISAT-District Level Data.csv
│
├── Jupyter Notebooks for analysis & visualization.ipynb
│
├── Key Insights for ICRISAT.pdf
│
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project folder

```bash
cd Indian-Agriculture-Data-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Jupyter Notebooks for analysis & visualization.ipynb
```

### 6. Run the notebook cells

Make sure the CSV dataset is in the correct project directory before running the notebook.

---

## 📌 Project Outcomes

The project converts raw district-level agricultural data into meaningful analytical information.

The analysis helps identify:

- Major crop areas
- Production trends
- State-wise differences
- Yield variations
- Relationships between area and production
- Crop diversity
- Potential outliers and unusual observations

The project demonstrates practical skills in **Python, Pandas, NumPy, Matplotlib, Seaborn, data cleaning, exploratory data analysis, statistical analysis, and data visualization**.

---

## 🔮 Future Scope

Possible extensions include:

- Advanced statistical analysis
- More detailed district-level comparisons
- Additional agricultural datasets
- Weather and rainfall data integration
- Machine learning-based crop yield prediction
- Interactive visualization dashboards

---

## 🏁 Conclusion

This project demonstrates how Python-based Exploratory Data Analysis can be used to understand complex agricultural datasets.

By analyzing **area, production, and yield** across crops, states, districts, and years, the project identifies important agricultural patterns and relationships. The combination of data cleaning, statistical analysis, correlation analysis, and visualization makes the dataset easier to interpret and provides a strong foundation for further agricultural data analysis.

---

## 👨‍💻 Author

**Shreya S S**

---

⭐ If you find this project useful, consider giving the repository a star.
