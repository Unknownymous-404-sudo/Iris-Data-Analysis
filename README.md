
# 📘 Iris Dataset Classification Analysis

This Jupyter Notebook performs a step-by-step analysis and visualization of the **Iris dataset** using Python, Pandas, Matplotlib, and Seaborn. It also includes basic data cleaning, exploration, visualization, and classification preparation steps.

---

## 📂 Contents

1. **Dataset Loading & Inspection**
   - Reads a CSV dataset (Iris)
   - Verifies column types and checks for missing values
   - Renames columns for clarity

2. **Data Cleaning**
   - Handles missing values (although none are present)
   - Ensures correct data types
   - Uses `try-except` for safe file handling

3. **Exploratory Data Analysis**
   - Displays basic statistical descriptions (`mean`, `std`, `min`, `max`, etc.)
   - Computes grouped means for each Iris species

4. **Visualizations**
   - 📈 **Line Chart**: Simulated trend of petal length over sample index
   - 📊 **Bar Chart**: Average petal length per species
   - 🟦 **Histogram**: Distribution of sepal width
   - ⚫ **Scatter Plot**: Sepal length vs. petal length colored by species

5. **Insights & Observations**
   - Identifies petal measurements as the most discriminative features
   - Notes that sepal dimensions show less variation among species

6. **Robust Error Handling**
   - Handles file loading errors (`FileNotFoundError`, `ParserError`, etc.)
   - Handles numeric conversion issues with appropriate logging

---

## 📦 Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

Install dependencies:
```bash
pip install pandas matplotlib seaborn
```

---

## 🧪 To Run

1. Open the notebook in Jupyter or Google Colab.
2. Make sure the Iris dataset CSV is in the same directory (or adjust the path).
3. Run cells top to bottom.

---

## 🧾 Author

This notebook was prepared as part of a classification project in the healthcare domain, focused on data handling and visualization using Python tools.
