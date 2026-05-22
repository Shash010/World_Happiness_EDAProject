# 🌍 World Happiness Report - Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?style=flat&logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-orange?style=flat&logo=plotly)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

> *"What makes a nation truly happy? Is it wealth, freedom, health - or something deeper?"*

An end-to-end Exploratory Data Analysis on the **World Happiness Report dataset (2005–2022)**, uncovering what drives happiness across 150+ countries.

---

## 📌 Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Key Visualizations](#key-visualizations)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)

---

## 📖 About the Project

The **World Happiness Report** is an annual survey by the Gallup World Poll that measures life satisfaction across nations. This project dives deep into the data to answer:

- Which countries are the happiest - and which are the least?
- What factors (GDP, health, freedom, corruption) drive happiness the most?
- How has global happiness changed over the years?
- Which regions of the world are consistently happier?

---

## 📦 Dataset

- **Source:** [Kaggle - World Happiness Report 2005–Present](https://www.kaggle.com/datasets/usamabuttar/world-happiness-report-2005-present)
- **Rows:** 2,199 records
- **Columns:** 13 features
- **Years covered:** 2005 - 2022
- **Countries:** 150+

### Key Columns:
| Column | Description |
|---|---|
| `happiness_score` | Life satisfaction score (0-10) |
| `gdp_per_capita` | Log GDP per capita |
| `social_support` | Having someone to count on |
| `life_expectancy` | Healthy life expectancy at birth |
| `freedom` | Freedom to make life choices |
| `generosity` | Charitable giving index |
| `corruption` | Perception of corruption |
| `positive_affect` | Positive emotions in daily life |
| `negative_affect` | Negative emotions in daily life |
| `govt_confidence` | Confidence in national government |

---

## 📁 Project Structure

```
World_Happiness_EDAProject/
│
├── World_Happiness_EDA.ipynb   # Main analysis notebook
└── README.md                   # Project documentation
```

---

## 📊 Key Visualizations

| # | Chart | Description |
|---|---|---|
| 1 | 🌍 World Map | Choropleth map of happiness by country |
| 2 | 🏆 Top & Bottom 10 | Happiest and saddest countries |
| 3 | 🔥 Correlation Heatmap | Factors driving happiness |
| 4 | 📈 Time Series | Global happiness trends over years |
| 5 | 🔵 Scatter Plot | GDP vs Happiness relationship |
| 6 | 📊 Regional Comparison | Happiness by world region |

---

## 🔑 Key Findings

1. **💰 Wealth matters, but isn't everything.**
   GDP per capita has the strongest correlation (0.78) with happiness, but social factors matter just as much.

2. **👫 Social support is the heart of happiness.**
   Having someone to count on (0.72 correlation) is nearly as important as wealth.

3. **🏥 Health = Happiness.**
   Life expectancy (0.71) shows that investing in public health directly translates to happier citizens.

4. **🗽 Freedom contributes meaningfully.**
   Personal freedom (0.53) - people need to feel in control of their lives to be happy.

5. **😤 Corruption is happiness's #1 enemy.**
   The strongest negative factor (-0.45) - corruption erodes trust and life satisfaction.

6. **🌍 Western Europe dominates.**
   Nordic countries (Finland, Denmark, Iceland) consistently top the rankings year after year.

7. **📈 Global happiness is slowly improving.**
   Despite fluctuations, the 2006–2022 trend shows gradual positive movement globally.

---

## 🛠️ Technologies Used

- **Python 3.10**
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib & Seaborn** - Static visualizations
- **Plotly Express** - Interactive choropleth map
- **Google Colab** - Development environment

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/Shash010/World_Happiness_EDAProject.git
```

2. Open the notebook in Google Colab or Jupyter:
```bash
jupyter notebook World_Happiness_EDA.ipynb
```

3. Run all cells from top to bottom ✅

> **Note:** A Kaggle API key is required to download the dataset automatically. Replace the credentials in the notebook with your own.

---

## 👤 Author

**Shashank Mekkiramane**  
[![GitHub](https://img.shields.io/badge/GitHub-Shash010-black?style=flat&logo=github)](https://github.com/Shash010)

---
