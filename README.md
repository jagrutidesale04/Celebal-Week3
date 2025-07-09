
#  Week 3: Energy Efficiency EDA & Visualization (Python + Jupyter)

This project is part of **Week 3** of the **Celebal Summer Internship** program.

The assignment was to perform **Exploratory Data Analysis (EDA)** using any dataset and present the results with **detailed visualizations**.  
I chose the **Energy Efficiency dataset** from the UCI Machine Learning Repository, and completed the analysis using **Python, Pandas, Seaborn, and Matplotlib** in a **Jupyter Notebook**.

---

##  Features

-  Excel file loaded directly with `pandas.read_excel()`
-  Full EDA including:
  - Shape, datatypes, summary stats
  - Null checks and data distributions
-  Feature Engineering:
  - `Total_Load` (Heating + Cooling)
  - Aspect Ratio & Glazing classification
-  Vibrant visualizations:
  - Histograms, boxplots, pie charts, heatmaps
  - Line plots, scatter plots, KDE plots
  - Pairplots for feature relationships
-  Insights explained after each major section
-  Final cleaned dataset exported as CSV

---

##  File Structure

```
Celebal-Week3/
├── eda_energy_efficiency.ipynb   # Main Jupyter Notebook
├── ENB2012_data.xlsx             # Original dataset
├── energy_efficiency_cleaned.csv# Cleaned dataset after EDA
├── requirements.txt              # Required Python packages
└── README.md                     # Project documentation (this file)
```

---

##  How to Run the Notebook

### 1.  Clone the Repository

```bash
git clone https://github.com/jagrutidesale04/Celebal-Week3.git
cd Celebal-Week3
```

### 2.  (Optional) Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate       # Windows
# OR
source venv/bin/activate    # macOS/Linux
```

### 3.  Install Dependencies

```bash
pip install -r requirements.txt
```

### 4.  Open the Notebook

```bash
jupyter notebook eda_energy_efficiency.ipynb
```

---

## Sample Visualizations

- Correlation heatmap
- Pairplot of selected features
- KDE plot of heating vs cooling load
- Boxplot of cooling load vs glazing distribution
- Pie chart of building orientations
- Scatter plot of compactness vs total load

---

## Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
openpyxl
```

##  Author

**Jagruti Desale**  
B.Tech – Data Science and Engineering (3rd Year)  
Summer Intern @ Celebal Technologies  

 [GitHub](https://github.com/jagrutidesale04)  
 [LinkedIn](https://www.linkedin.com/in/jagruti-desale-jd04)

---

## License

This project is intended for educational use as part of Celebal’s summer internship program. You are welcome to fork and experiment for learning purposes!
