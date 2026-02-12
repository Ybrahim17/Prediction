# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

<div align="center">
  <img src="images/spacex_banner.png" alt="SpaceX Banner" width="100%" />
  
  ### Predicting Falcon 9 Landing Success with Machine Learning
  
  **IBM Data Science Capstone Project**
  
  [📊 Live Dashboard](#) | [📄 Presentation](presentation/SpaceX_Capstone.pdf) | [📓 Notebooks](#notebooks)
  
</div>

---

## 📋 Table of Contents

- [About](#about)
- [Problem Statement](#problem-statement)
- [Project Highlights](#project-highlights)
- [Demo](#demo)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Results](#results)
- [Notebooks](#notebooks)
- [Dashboard](#dashboard)
- [Key Insights](#key-insights)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 📖 About

This data science project analyzes **90+ SpaceX Falcon 9 launches** from 2010 to 2020 to predict the success of first-stage rocket landings. By leveraging machine learning classification models, we achieved **83.3% prediction accuracy**, enabling cost estimation and competitive analysis in the commercial space launch industry.

### 🎯 Why This Matters

SpaceX revolutionized space economics through reusable rocket technology:
- **Traditional launches:** $165 million per launch
- **SpaceX Falcon 9:** $62 million per launch
- **Cost savings:** $103 million (~62% reduction)

Predicting landing success allows competitors to:
- Estimate launch costs accurately
- Make informed bidding decisions
- Understand factors driving success rates

---

## ❓ Problem Statement

**Can we predict if the Falcon 9 first stage will land successfully?**

SpaceX advertises Falcon 9 rocket launches at a significantly lower cost than competitors. The cost advantage comes from their ability to reuse the first stage. Determining whether the first stage will land successfully is crucial for estimating launch costs and understanding SpaceX's competitive positioning.

### Research Questions

1. What factors influence landing success?
2. How has the success rate evolved over time?
3. Which launch sites have the highest success rates?
4. How does payload mass affect landing outcomes?
5. Can we reliably predict landing success for cost estimation?

---

## ⭐ Project Highlights

- ✅ **90+ launches analyzed** spanning 2010-2020
- ✅ **Multiple data sources:** SpaceX API + Web Scraping
- ✅ **Comprehensive EDA:** SQL, Visualizations, Interactive Maps
- ✅ **4 ML models compared:** Logistic Regression, SVM, Decision Tree, KNN
- ✅ **83.3% accuracy** achieved with SVM model
- ✅ **Interactive dashboard** built with Plotly Dash
- ✅ **Geographic analysis** using Folium maps
- ✅ **Production-ready code** with proper documentation

---

## 🎬 Demo

### 📊 Interactive Dashboard

<div align="center">
  <img src="images/dashboard_demo.gif" alt="Dashboard Demo" width="80%" />
  <p><em>Plotly Dash dashboard for dynamic data exploration</em></p>
</div>

### 🗺️ Launch Site Map

<div align="center">
  <img src="images/folium_map.png" alt="Folium Map" width="80%" />
  <p><em>Interactive map showing launch sites and outcomes</em></p>
</div>

### 📈 Success Rate Evolution

<div align="center">
  <img src="images/success_trend.png" alt="Success Trend" width="80%" />
  <p><em>Dramatic improvement from 40% to 95% success rate</em></p>
</div>

---

## 🛠️ Technologies

### Languages & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Libraries & Frameworks

**Data Processing & Analysis:**
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `sqlite3` - Database operations

**Data Visualization:**
- `matplotlib` - Static plotting
- `seaborn` - Statistical visualization
- `plotly` - Interactive charts
- `folium` - Interactive maps

**Machine Learning:**
- `scikit-learn` - ML models and evaluation
- `GridSearchCV` - Hyperparameter tuning

**Web & Data Collection:**
- `dash` - Interactive dashboard
- `requests` - HTTP requests
- `beautifulsoup4` - Web scraping

---

## 📥 Installation

### Prerequisites

- Python 3.9 or higher
- pip package manager
- Git

### Step-by-Step Setup
```bash
