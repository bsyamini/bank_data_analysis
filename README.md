# bank_data_analysis
## Bank Marketing Data Analysis
This project analyzes a Portuguese banking dataset to uncover customer behaviors and campaign effectiveness through data cleaning, statistical insights, and visualizations. It demonstrates end-to-end data analytics skills using Python for portfolio showcase.

## Project Overview
A comprehensive analysis of bank marketing campaigns identifying key success factors like customer job types, campaign contacts, and duration patterns. Hidden insights reveal optimal strategies for subscription success, supporting data-driven business decisions.
​

# Dataset
Source: Portuguese Bank Marketing dataset ( UCI ML Repository equivalent)

Size: 45,000 customer records

Focus: Predict subscription success ('yes'/'no') via customer demographics and interaction data

# Tools & Libraries
Jupyter Notebook: Interactive analysis environment

Pandas & NumPy: Data loading, cleaning, feature engineering (balance/age ratios, bins)

Matplotlib & Seaborn: Statistical charts (histograms, boxplots, KDE, jointplots, pie charts)

# Analysis Steps
Data Loading: Import CSV via pd.read_csv(), create working copy df_analysis = df.copy()

Cleaning: Handle invalid ages, verify data integrity, no new columns created in original
​

# Exploratory Analysis:

Crosstabs (job vs marital by campaign sum)

Unique values (education, job categories)

Feature engineering (balance_age_ratio)

Insights Extraction: Groupby metrics (avg duration/success by campaign, department rates)
​
```
Bank-Marketing-Analysis/
│
├── README.md                 # Project documentation (copy below)
├── data/
│   ├── bank_data.csv         # Raw dataset (~45K records)
│   └── README.md             # Data description
├── notebooks/
│   └── bank_analysis.ipynb   # Main analysis notebook
├── outputs/
│   ├── balance_age_boxplot.png
│   ├── campaign_duration_jointplot.png
│   ├── success_kde.png
└── ├── dept_success_pie.png

```

# Visualizations Created
Chart Type	Purpose	Key Insight
Histogram → Boxplot	Balance/Age ratio distribution	Outlier detection in customer ratios 
​
Bar → Jointplot	Duration by campaign contacts	Relationship between contacts and call length
Bar → KDE Plot	Success rate by campaign	Density of successful vs unsuccessful campaigns 
​
Bar → Pie Chart	Success by department	Proportional performance across jobs 
​
## Key Findings
- Higher contacts → longer duration, lower success
- Job-specific performance patterns identified

## Skills Demonstrated
Data cleaning, EDA, feature engineering, advanced visualizations, Git workflows

