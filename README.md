# Singapore-Public-Housing-Analysis
This repository contains a comprehensive analysis of Singapore’s public housing system, focusing on affordability and demand trends. It includes data cleaning, sentiment analysis, and visualization outputs used in the white paper and presentation.

## Highlights:
- Word cloud analysis derived from public sentiment data.
- Oversubscription rate analysis with visualized results (bar graph).
- White paper presenting findings and actionable recommendations.

---

## File Descriptions

### 1. White Paper and Presentation
- **WhitePaper.pdf**: A detailed analysis of Singapore’s public housing system with findings and recommendations.
- **Presentation.pdf**: A visual summary of the white paper.

### 2. Data Files
#### Raw Data:
- **Over_subscription_rate.xlsx**:
  - Contains raw data on oversubscription rates for Build-to-Order (BTO) flats.
  - Includes a **bar graph** summarizing oversubscription trends.
- **Working_file_1.xlsx**:
  - Source data for text-based analysis and visualization in R.

#### Cleaned Data:
- **Affordability.txt**:
  - Cleaned data capturing affordability-related commentary.
- **Tries.txt**:
  - Cleaned data on public experiences with housing applications.

### 3. R Markdown Scripts
- **Affordability_topic_analysis.Rmd**:
  - Script for sentiment and word cloud analysis using `Affordability.txt`.
- **BTO_tries_wordcount.Rmd**:
  - Word count analysis of `Tries.txt`, leading to visualizations in the white paper.

---

## Data Cleaning and Analysis Workflow

### Data Cleaning and Analysis Process
1. **Raw Data Overview**:
   - Raw data was sourced from `Over_subscription_rate.xlsx` (oversubscription rates) and `Working_file_1.xlsx` (commentary).

2. **Cleaning Steps**:
   - Removed duplicates and handled missing values.
   - Standardized text formatting for consistency.
   - Saved cleaned data in `.txt` format for analysis.

3. **R Analysis**:
   - `Affordability.txt` and `Tries.txt` were processed in R for sentiment analysis and visualization.
   - Outputs include a word cloud (used in the white paper) and additional unused results.

---

## Highlights of Analysis
- **Word Cloud**: Showcases public sentiment on housing affordability and oversubscription challenges.
- **Bar Graph**: Visualizes oversubscription rates across various BTO estates and flat types.

---

