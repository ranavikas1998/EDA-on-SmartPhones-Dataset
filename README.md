#  EDA on Smartphones Dataset

> Exploratory Data Analysis (EDA) of a smartphones dataset to uncover patterns in price, features, performance, and brand trends.

---

##  Overview  
This project performs comprehensive **EDA on a smartphones dataset** using Python libraries like `pandas`, `matplotlib`, `seaborn`, and `plotly`.  
It investigates which smartphone brands, specs, and features are most prevalent, and how they impact consumer trends.

---

##  Highlights & Insights
- **Top Brands & Price Range**: Identify the most common brands and explore price distribution and outliers.
- **Feature Popularity**: Analyze features like RAM, internal storage, cameras, and processor brands.
- **Technology Trends**: Examine the prevalence of 5G, NFC, IR blasters, and operating system usage.
- **Correlation Analysis**: Investigate relationships between price, rating, and features using bivariate plots.
- **Visualizations**: A mix of histograms, KDE plots, boxplots, bar charts, pie charts, scatter plots, and heatmaps.

---

##  Tools & Technologies
- **Python Libraries**:
  - `pandas`, `numpy` – data cleaning & manipulation
  - `matplotlib`, `seaborn` – static visualizations
  - `plotly` – interactive plots
- **Environment**: Jupyter Notebook or `.py` scripts for reproducibility.

---

##  Project Structure
```
EDA-on-SmartPhones-Dataset/
├── data/
│   └── smartphones.csv        # Raw dataset
├── notebooks/
│   └── eda_smartphones.ipynb  # Jupyter notebook with EDA and visual analysis
├── visuals/
│   ├── brand_distribution.png
│   ├── price_kde.png
│   └── feature_corr_heatmap.png
├── code/
│   └── eda_smartphones.py     # Executable script version of EDA
├── README.md                  # Project documentation
└── requirements.txt           # Required Python packages
```

---

##  How to Run
1. **Clone the repo**  
   ```bash
   git clone <this-repo-url>
   cd EDA-on-SmartPhones-Dataset
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Perform EDA**  
   - Open `notebooks/eda_smartphones.ipynb` for an interactive walkthrough.
   - Or run the script:
     ```bash
     python code/eda_smartphones.py
     ```
   - Visuals will be saved in `visuals/`.

---

##  Suggested Analysis Outline
1. **Data Cleaning**
   - Handle missing/null values (e.g., price, rating)
   - Remove duplicates and inconsistent entries
   - Standardize units and categorical fields

2. **Univariate Analysis**
   - Price distribution (histogram, KDE, boxplot)
   - Brand frequency (bar chart)
   - Feature prevalence (pie charts/bar plots)

3. **Bivariate Analysis**
   - Price vs. rating (scatter plot)
   - Price vs. brand or features (bar charts with error bars or boxplots)
   - Correlation heatmap to spot multicollinearity

4. **Feature Insights**
   - Identify which specs are most common (e.g., RAM, storage, cameras)
   - Assess impact of premium features (e.g., 5G) on pricing
   - Explore OS distribution (iOS vs. Android)

5. **Conclusion**
   - Summarize key insights and actionable trends
   - Discuss data limitations and possible further analysis (e.g., regression modeling)

---

##  Author & Contact
**Vikas Rana** — Data Analyst & BI Developer  
GitHub: [ranavikas1998](https://github.com/ranavikas1998)  
Email: (Add your email here)

---


