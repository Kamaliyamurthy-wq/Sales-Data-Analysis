  Sales Data Analysis Project

 Introduction
This project presents a detailed analysis of a retail sales dataset to understand customer purchasing behaviour. The goal is to identify high-value customer segments based on demographic, geographic, and professional attributes.
The insights derived from this analysis help in making data-driven decisions in marketing, sales strategy, and customer targeting.

  Project Objectives
- Analyse customer spending patterns across:
  - Gender
  - Age Group
  - State
  - Occupation
  - Product Category
  - Marital Status
- Identify high-value customer segments
- Generate actionable business insights using data analysis and visualization

  Dataset Overview
The dataset contains customer-level retail transaction records in CSV format.

Each record includes:
- Demographics: Gender, Age, Marital Status
- Location: State, Zone
- Professional Info: Occupation
- Transaction Details: Product Category, Orders, Amount

Primary Metric: Sales Amount (Total purchase value)

 Tools & Technologies Used
- Python
- Pandas & NumPy (Data Cleaning & Analysis)
- Matplotlib & Seaborn (Data Visualization)
- Google Colab

 Data Cleaning & Preparation
- Removed unnecessary columns (`Status`, `unnamed1`)
- Handled missing values in `Amount`
- Renamed columns for better readability
- Standardized categorical values:
  - Gender: `F - Female`, `M - Male`
  - Marital Status: `0 - Single`, `1 - Married`
- Ensured consistency across dataset

 Exploratory Data Analysis (EDA)

Gender-wise Analysis
- Female customers contribute more to total sales than male customers

Age Group Analysis
- Age group 26–35 are the highest spenders

State-wise Analysis
- Top performing states:
  - Uttar Pradesh
  - Maharashtra
  - Karnataka

Occupation Analysis
- High spending observed in:
  - IT
  - Healthcare
  - Banking

Product Category Analysis
- Certain product categories generate consistently higher revenue

Marital Status Analysis
- Single customers spend more compared to married customers

Data Visualization
- Used bar charts and comparative plots
- Helped identify trends and patterns clearly

Key Findings
- Female customers are the primary contributors to sales
- Age group 26–35 is the most valuable segment
- Few states dominate total sales
- IT, Healthcare, and Banking professionals spend more
- Single customers show higher purchasing behaviour

Business Recommendations
- Target female customers aged 26–35 with marketing campaigns
- Focus on top-performing states for promotions
- Create offers for high-income professional groups
- Optimize inventory based on top product categories

Conclusion
This project demonstrates how raw data can be transformed into meaningful business insights using data cleaning, analysis, and visualization techniques.
It highlights the importance of data-driven decision-making in improving marketing strategies and customer segmentation.

