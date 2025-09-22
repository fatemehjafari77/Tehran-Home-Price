# Tehran-Home-Price
# 📊 Data Analysis & Visualization Project

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-1.6-green?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-orange?logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-purple?logo=seaborn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-1.11-lightblue?logo=scipy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3-yellow?logo=scikitlearn&logoColor=black)

## 🔍 Project Overview
This project focuses on **data cleaning, visualization, correlation analysis, and house recommendation** using Python.
The workflow includes extracting data from files, cleaning it, detecting outliers, analyzing relationships between variables, and recommending houses based on user criteria.

## 🛠 Libraries Used
- `numpy` – for numerical computations
- `pandas` – for data manipulation and cleaning
- `matplotlib` – for plotting histograms and visualizations
- `seaborn` – for advanced statistical plots like boxplots and violin plots
- `scipy.stats` – for Pearson correlation and statistical analysis
- `sklearn` – for additional preprocessing and analysis tools

## ⚡ Activities Performed
1. **Data Cleaning**
- Extracted data from files and converted it into a DataFrame.
- Removed missing values and standardized formats.

2. **Outlier Detection**
- Used mean and IQR to detect extreme values.
- Highlighted outliers in the dataset.

3. **Data Visualization**
- Histograms to observe distributions.
- Box plots to show spread and identify outliers.
- Violin plots to visualize density and distribution.
- Pair plots to explore relationships between variables.

4. **Correlation Analysis**
- Calculated **Pearson correlation coefficients** to find linear relationships.
- Generated **correlation matrices** to visualize all pairwise relationships.
- Textual descriptions of correlation types included in a separate file.

5. **House Recommendation**
- Recommended the **top 5 houses** closest to the user's target price and matching the specified features (Address, Room, Parking, Elevator, Warehouse).

## 🖥 Installation & Usage


📂 Project Structure
Data-Analysis-Project/
│
├─ data/                  # Original datasets
├─ main.py                # Main analysis & recommendation script
├─ plots/                 # Generated plots (histograms, boxplots, violin plots, pairplots)
├─ correlations.txt       # Textual description of correlations
├─ README.md              # Project documentation
└─ requirements.txt       # Python dependencies


📊 Sample Plots
•	Histogram – shows distribution of each variable.
•	Box Plot & Violin Plot – visualize spread, density, and outliers.
•	Pair Plot – observe relationships and correlations between features.
•	Correlation Matrix – numeric view of relationships using Pearson correlation


1. Clone the repository:
```bash
git clone https://github.com/YourUsername/Data-Analysis-Project.git
