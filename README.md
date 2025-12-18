# YouTube Shorts Learning Trend Analyzer

## Overview
This project analyzes learning-focused YouTube Shorts to understand what drives engagement, view growth, and viral behavior across different educational categories such as Travel Learning, Career Tips, Study Skills, Finance, Soft Skills, AI Tools, and Tech Skills.

The objective is to identify data-driven patterns that distinguish viral Shorts from non-viral content and present insights through clear analysis and dashboards.

---

## Problem Statement
Short-form educational content is growing rapidly, but creators and analysts often lack clarity on:
- What makes a learning-focused Short go viral
- How engagement varies across learning categories
- Whether high views always translate to meaningful engagement

This project addresses these challenges using structured data analysis and visualization.

---

## Dataset
- Source: YouTube Data API  
- Content Type: Learning-focused YouTube Shorts  
- Level: Video-level metadata  

Key features include:
- Views, likes, comments
- Engagement rate
- Category labels
- Growth-related metrics

The cleaned dataset is available in the `data/` folder.

---

## Methodology
1. **Data Collection**  
   Extracted YouTube Shorts metadata using the YouTube Data API.

2. **Data Cleaning & Preparation**  
   Removed duplicates, handled missing values, and standardized data formats.

3. **Feature Engineering**  
   Calculated engagement rate and derived growth-based metrics for analysis.

4. **Viral Detection**  
   Applied IQR-based outlier detection to identify viral Shorts.

5. **Exploratory Data Analysis**  
   Analyzed engagement and growth trends across categories.

6. **Visualization & Dashboarding**  
   Built a Power BI dashboard to present insights clearly.

---

## Key Insights
- Viral Shorts show clear spikes in growth compared to non-viral content.
- High view counts do not always indicate high engagement.
- Engagement rate is a stronger metric for comparing performance across categories.
- Certain learning categories consistently outperform others in engagement.

---

## Project Structure
Below is the high-level structure of the repository:

youtube-shorts-learning-trend-analyzer/
├── notebooks/ # Python analysis notebooks
├── data/ # Cleaned dataset
├── reports/ # Final project report
├── dashboard/ # Power BI dashboard
└── README.md # Project overview


---

## Tools & Technologies
- Python (Pandas, NumPy)
- YouTube Data API
- Power BI
- Excel
- Jupyter Notebook

---

## Outcomes
- End-to-end analytics project from data collection to insights
- Clean, reproducible analysis notebook
- Research-style analytical report
- Interactive dashboard for stakeholder interpretation

---

## Author
**Devika Kadam**  
Master’s in Business Analytics  
Aspiring Data / Business Intelligence Analyst
