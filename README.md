  # COVID-19 and Zoo Dataset Analysis Using Pandas

This repository contains a Jupyter Notebook that demonstrates data analysis, merging, cleaning, and visualization using Python's Pandas, Matplotlib, and Seaborn libraries.

## 📁 Datasets Used

- **Zoo dataset** (CSV): Includes animal data for merging practice
- **COVID-19 India dataset** (Excel): State-wise COVID statistics

## ✅ Key Operations Performed

### 🐾 Zoo Dataset:
- Inner, outer, left, and right joins using `pd.merge()`
- Sorting and resetting indexes
- Filling missing values using `.fillna()`

### 🦠 COVID-19 Dataset:
- Exploratory Data Analysis: `.describe()`, `.info()`, `.shape`
- Filtering data by `Active` and `Deaths` counts
- Grouping and summarizing top 5 states by deaths
- Filling missing values using:
  - Mean
  - Median
  - Mode

### 📊 Visualization:
- Bar plots of:
  - Active COVID-19 cases by state
  - Total deaths per state

----

### 🙋‍♂️ Author
Aman Khokhar | B.Tech (AI) @ Ganpat University  
🌐 LinkedIn: [linkedin.com/in/amankhokhar293](https://linkedin.com/in/amankhokhar293)

```bash
pip install pandas numpy matplotlib seaborn openpyxl

