# Automated Market Research & Competitive Hiring Analysis

This project was developed as part of a Summer Internship at **Peterson Technology Partners (PTP)**. The goal was to use AI and data-driven techniques to analyze hiring trends, salary benchmarks, and in-demand skills using a real-world dataset of 100,000 US Tech Jobs.



## Dataset Overview

- Source: [Kaggle – 100K US Tech Jobs Winter 2024](https://www.kaggle.com/datasets/christopherkverne/100k-us-tech-jobs-winter-2024)
- Collected between: **Oct 2024 – Dec 2024**
- Domains covered:
  - **Software Engineering**
  - **Data Science**
  - **IT / Infrastructure**
  - **Product Management**
  - **Cybersecurity**


## Internship Project Focus

**Automated Market Research & Competitive Analysis**:
- Track hiring trends across roles & locations
- Benchmark salaries by role, state, and company
- Identify top companies hiring freshers & international students (CPT/OPT-friendly)
- Extract top **skills** and **programming languages** per job category



## Key Features in the Notebook

| Analysis Module | Description |
|-----------------|-------------|
| Hiring Trends | Most in-demand roles |
| Salary Analysis | Avg/median salaries by role, company, location |
| Top Skills | Extracted using TF-IDF from job descriptions |
| Top Programming Languages | Parsed using NLP per job category |
| CPT/OPT Friendly Detection | Based on keywords like "CPT", "OPT", "visa sponsorship" |
| Fresher-Friendly Jobs | Flagged jobs for candidates with 0–1 years of experience |
| Visualizations | Pie charts, bar plots, and heatmaps for easy insight |



## Sample Visualizations

- Job distribution by category  
- Salary heatmap by state  
- Top programming languages (pie charts)  
- WordClouds of skillsets  
- CPT/OPT-friendly company rankings  



## How to Use

1. Open the notebook: `market_analysis.ipynb`
2. Follow the cells step-by-step — from cleaning → analysis → visualization
3. Try changing filters for your own role (e.g., filter only `Product Management` jobs)
4. Results can be exported as `.csv` or visual assets for reports



## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- NLP: TF-IDF, WordCloud
- Visualization: Matplotlib, Pie Charts, Bar Charts
- Google Colab + GitHub for collaboration

