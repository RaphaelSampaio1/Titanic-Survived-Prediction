# Titanic Data Analysis 🚢📊  

This repository contains an in-depth analysis of the Titanic dataset, exploring relationships between variables, identifying outliers, and creating visualizations to better understand the data and the dynamics of the disaster.  

---

## 📁 Project Structure  

- **`data/`**: Contains raw and processed datasets.  
- **`notebooks/`**: Jupyter notebooks with data cleaning, analysis, and visualization.  
- **`src/`**: Source code for data preprocessing and custom analysis scripts.  
- **`reports/`**: Includes final visualizations and reports summarizing the findings.  

---

## 🚀 Features  

- **Exploratory Data Analysis (EDA)**: Detailed analysis to uncover trends and insights.  
- **Data Cleaning**: Handling missing data and outliers for reliable analysis.  
- **Visualizations**: Clear and impactful charts to showcase patterns.  
- **Modeling (Optional)**: Machine learning predictions based on survival likelihood.  

---

## 📊 Tools and Technologies  

- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Jupyter Notebook** for interactive analysis.  

---

Aqui está o conteúdo estruturado em um modelo de README para GitHub:

---

# Titanic Data Analysis 🛳️

This repository contains an exploratory data analysis (EDA) of the Titanic dataset. The analysis includes various statistical and visualization techniques to understand the relationships between features and survival rates.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Libraries Used](#libraries-used)  
4. [Key Insights](#key-insights)  
5. [Visualization Highlights](#visualization-highlights)  
6. [Null Value Handling](#null-value-handling)  
7. [Correlation Analysis](#correlation-analysis)  
8. [How to Run](#how-to-run)  
9. [License](#license)

---

## Project Overview

This project analyzes the Titanic dataset to uncover patterns in survival rates based on various features such as age, fare, class, and family relationships. The analysis explores both visual and statistical approaches to interpret the data and its correlations.

---

## Dataset Description

| **Column**      | **Description**                                          |
|------------------|----------------------------------------------------------|
| `Survived`      | Survival status: `0 = No`, `1 = Yes`                      |
| `Pclass`        | Ticket class: `1 = 1st`, `2 = 2nd`, `3 = 3rd`             |
| `Sex`           | Sex of the passenger                                      |
| `Age`           | Age in years                                              |
| `SibSp`         | Number of siblings/spouses aboard the Titanic             |
| `Parch`         | Number of parents/children aboard the Titanic             |
| `Ticket`        | Ticket number                                             |
| `Fare`          | Passenger fare                                            |
| `Cabin`         | Cabin number                                              |
| `Embarked`      | Port of embarkation: `C = Cherbourg`, `Q = Queenstown`, `S = Southampton` |

---

## Libraries Used

- **Pandas**: For data manipulation and analysis  
- **Matplotlib**: For plotting and visualization  
- **Seaborn**: For advanced visualizations  
- **YData Profiling**: For comprehensive dataset profiling  

---

## Key Insights

- **Fare Distribution**:  
  The majority of passengers paid low fares, with very few paying extremely high fares.

- **Age and Family Relationships**:  
  Most passengers under 40 had at least one partner or family member aboard.  

- **Survival Correlation**:  
  Survivors were likely to be:  
  - Under 40 years old  
  - Traveling in 1st or 2nd class  
  - Traveling alone or with fewer family members  

---

## Visualization Highlights

1. **Bar Chart of Unique Values per Column**  
   - Shows the cardinality of each column.  

2. **Fare Histogram**  
   - Highlights the concentration of low-cost tickets.  

3. **Scatter Plot (Age vs. Number of Family Members)**  
   - Identifies relationships between age and family size.  

4. **Pair Plot**  
   - Displays relationships between survival and features like class, age, and fare.  

5. **KDE Plot**  
   - Visualizes density distributions of `Pclass` and `Fare` grouped by survival status.  

6. **Heatmap**  
   - Correlation matrix for numerical features.  

---

## Null Value Handling

### Strategy:

1. **`Age` Column**:  
   Replaced null values with the mean age of the dataset.  

2. **`Cabin` and `Embarked` Columns**:  
   Analyzed relationships between null values and other features to ensure data consistency.

---

## Correlation Analysis

- **Negative Correlations**:  
  - `Pclass` and `Fare`  
  - `Survived` and `Sex`  

- **Insights**:  
  - Cheaper tickets often corresponded to lower classes.  
  - Males had a lower survival rate compared to females.  

## 📋 Usage  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/titanic-data-analysis.git
   ```  

2. Navigate to the project folder:  
   ```bash
   cd titanic-data-analysis
   ```  
3. Run the notebooks or scripts to explore the dataset and generate insights.  

---

## 🌟 Contribution  

Contributions are welcome! If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.  

---

## 📧 Contact  

If you have any questions or suggestions, feel free to contact me:  
**Email**: raphaelsantos.jan@gmail.com  
**GitHub**: [Raphael Sampaio]([https://github.com/your-username](https://github.com/RaphaelSampaio1/))  
```
