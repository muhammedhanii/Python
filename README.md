# Social Media Performance Analysis Notebook

## Overview
This repository contains a comprehensive Jupyter/Google Colab notebook for analyzing social media performance data across 52 weeks and 4 major platforms (Facebook, Instagram, LinkedIn, and X).

## Files in This Repository

- **Social_Media_Analysis_Notebook.ipynb** - Main analysis notebook
- **FACEBOOK.xlsx** - Facebook performance data (52 weeks)
- **INSTAGRAM.xlsx** - Instagram performance data (52 weeks)
- **LINKEDIN.xlsx** - LinkedIn performance data (52 weeks)
- **X.xlsx** - X (formerly Twitter) performance data (52 weeks)
- **Project_DS2526.pdf** - Project instructions and requirements

## Data Schema

Each Excel file contains the following columns:
- Social_Media
- Week (1-52)
- Impressions
- Engagement Rate
- Audience Growth Rate
- Response Rate
- Post Reach
- Likes

## Notebook Contents

The notebook includes the following sections:

### 1. File Upload + Imports
- File upload functionality for Google Colab
- Import of required libraries (pandas, numpy, matplotlib, seaborn)

### 2. Data Loading
- Load all 4 Excel files
- Display confirmation messages

### 3. Data Consolidation
- Schema validation
- Explanation of merge vs append approach
- Combine all platform data into single DataFrame
- Display total rows and unique platforms

### 4. Exploratory Data Analysis (EDA)
- Dataset information and statistics
- Summary statistics
- Missing values analysis
- Weekly data completeness check
- Data quality assessment

### 5. Analytical Questions
- **Q1:** Which platform has the highest average engagement rate?
- **Q2:** Which platform shows the most consistent performance?
- **Q3:** How do all metrics compare across platforms?

### 6. Visualizations
1. **Bar Chart** - Average Engagement Rate per Platform
2. **Scatter Plot** - Impressions vs Likes (colored by platform)
3. **Line Plot** - Engagement Rate over 52 weeks for each platform
4. **Box Plot** - Audience Growth Rate variability per platform
5. **Bar Plot** - Response Rate comparison across platforms

### 7. Final Summary
- Key insights from the analysis
- Most engaging platform
- Most consistent platform
- Notable trends in performance
- Strategic recommendations

## How to Use

### Option 1: Google Colab (Recommended)
1. Upload the notebook to Google Colab
2. Uncomment the file upload cell
3. Run the file upload cell and upload all 4 Excel files
4. Run all cells sequentially (Runtime → Run all)

### Option 2: Local Jupyter
1. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl jupyter
   ```
2. Ensure all 4 Excel files are in the same directory as the notebook
3. Open the notebook:
   ```bash
   jupyter notebook Social_Media_Analysis_Notebook.ipynb
   ```
4. Run all cells sequentially

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl (for reading Excel files)
- jupyter or Google Colab

## Output

The notebook generates:
- Statistical analysis and insights
- 5 professional visualizations
- Detailed answers to analytical questions
- Strategic recommendations based on data

## Features

✅ Complete data consolidation and validation  
✅ Comprehensive exploratory data analysis  
✅ Professional visualizations with proper formatting  
✅ Statistical analysis and comparisons  
✅ Business insights and recommendations  
✅ Runs top-to-bottom without errors  
✅ Well-commented and documented code  

## Author

Data Science Final Project - Social Media Performance Analysis

## License

This project is for educational purposes.
