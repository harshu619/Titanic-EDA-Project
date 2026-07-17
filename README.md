# Titanic Exploratory Data Analysis (EDA)

## 📖 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis includes data loading, cleaning, handling missing values, statistical summaries, and visualizations to identify patterns and relationships that influenced passenger survival.

---

## 🎯 Objectives

- Understand the structure of the dataset.
- Clean and preprocess the data.
- Handle missing values and duplicate records.
- Explore relationships between different features.
- Visualize important trends using graphs.
- Draw meaningful insights from the data.

---

## 📂 Dataset

- **Dataset:** Titanic - Machine Learning from Disaster
- **Source:** Kaggle
- **File Used:** `train.csv`

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Analysis Performed

- Data Loading
- Data Inspection
- Summary Statistics
- Missing Value Detection
- Missing Value Handling
- Duplicate Value Check
- Correlation Analysis
- Heatmap
- Histogram
- Survival Count Plot
- Gender Distribution
- Survival by Gender
- Passenger Class Analysis
- Box Plot
- Scatter Plot
- Pair Plot

---

## 📈 Key Insights

- The dataset contains **891 passenger records**.
- Missing values were found in the **Age**, **Cabin**, and **Embarked** columns.
- Missing values in **Age** were filled using the median.
- Missing values in **Embarked** were filled using the most frequent value (mode).
- The **Cabin** column was removed because it contained many missing values.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had better survival rates than second- and third-class passengers.
- Most passengers were between **20 and 40 years** of age.

---

## 📁 Project Structure

```
Titanic-EDA-Project/
│
├── Titanic_EDA.ipynb
├── train.csv
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open **Jupyter Notebook**.
4. Open **Titanic_EDA.ipynb**.
5. Run all cells to reproduce the analysis.

---

## 🚀 Future Improvements

- Build a machine learning model to predict passenger survival.
- Create an interactive dashboard using Plotly or Streamlit.
- Perform feature engineering for better analysis.

---

## 👩‍💻 Author

**Sri Divya Harshini Nittala**

B.Tech, Civil Engineering

Indian Institute of Technology (ISM) Dhanbad

---

## 📜 License

This project is licensed under the **MIT License**.
