# Predictive Modelling for COVID-19 in Public Health

## Overview
This project applies data science techniques to analyze and model the global COVID-19 pandemic. The goal is to generate actionable insights for public health organizations to inform policy, allocate healthcare resources, and predict future outbreak trends.

## Objectives
- Analyze global COVID-19 data trends and identify patterns
- Engineer features to better understand the progression of the pandemic
- Compare outbreak trends across countries, including China and the Top 10 most affected countries
- Cluster countries based on pandemic behavior for targeted insights
- Attempt time series forecasting using ARIMA
- Present insights with visualizations and a structured report

## Dataset
- **Source**: COVID-19 Open Research Dataset (CORD-19) on Kaggle
- **Includes**: Daily confirmed cases, deaths, recoveries, demographic data

## Project Structure
```bash
📁 COVID-19-Predictive-Modeling/
├── 📁 data/                  # Raw and cleaned data
├── 📁 notebooks/             # Jupyter notebooks with analysis
├── 📁 visuals/               # Charts and plots used in the report/presentation
├── 📁 report/                # Final report and presentation slides
├── requirements.txt          # Python dependencies
└── README.md                 # Project overview and instructions
```

## Key Techniques Used
- **Data Cleaning & Merging**: Handling missing values, standardizing formats, merging multiple files
- **Feature Engineering**: Created metrics such as cases/deaths per 1,000, mortality & recovery ratios
- **Exploratory Data Analysis (EDA)**: Visualized growth, trends, and correlations
- **Clustering Analysis**: Grouped countries using K-Means based on COVID-19 metrics
- **Time-Series Forecasting**: Applied ARIMA to project future cases (with discussion on stationarity challenges)

## Tools & Technologies
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- Jupyter Notebook
- Git & GitHub for version control

## How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/Pholoy/COVID-19-Predictive-Modeling.git
   cd COVID-19-Predictive-Modeling
   ```
2. Install required packages
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebooks in the `notebooks/` folder.

## Results & Insights
- China showed early control, while countries like the U.S. and Brazil faced prolonged high growth.
- Clustering revealed three distinct groups of countries based on pandemic severity.
- Time series analysis provided insights but highlighted the limitations of ARIMA due to non-stationarity.

## Deliverables
- 📄 Final report with analysis and insights
- 🧾 Well-documented Jupyter notebooks
- 📊 Presentation slides summarizing the findings

## Author
**Oyekola Oluwasegun Philips**  
Cohort 2 Fellow, 3MTT Nigeria — Data Science Track  
📧 Email: pholoy01@gmail.com  
🔗 GitHub: [Pholoy](https://github.com/Pholoy)  
🔗 LinkedIn: [poyekol](https://www.linkedin.com/in/poyekol)
