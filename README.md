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
- **Over_Subscription_Data.xlsx**:
  - Started off with raw data on oversubscription rates for Build-to-Order (BTO) flats.
  - Cleaned data and created pivot table views.
  - Created a **bar graph** summarizing oversubscription trends.
- **Housing_Sentiment_Data.xlsx**:
  - Scrapped Reddit for posts and comments.
  - Cleaned phrases for two topics: balloting tries and affordability.
  - Extracted counts for key phrases.

#### Cleaned Data:
- **Affordability.txt**: Phrases capturing affordability-related sentiment.
- **Tries.txt**: Phrases on sentiment regarding housing applications.

### 3. R Markdown Scripts
- **Affordability_Topic_Analysis.Rmd**:
  - Script for sentiment and word cloud analysis using `Affordability.txt`.
- **BTO_Tries_Wordcount.Rmd**:
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

## Future work
While this analysis focuses on affordability patterns based on available housing and income data, it does not model the behavioral or long-term impacts of potential policy changes. Expanding the project using dynamic simulations or agent-based modeling could help capture how different types of agents , such as public housing buyers, sellers, and policymakers respond over time.

Concepts from microeconomics, including asymmetric information, signaling, and externalities, would be relevant to such an approach. These models could simulate how individual decisions aggregate to affect market outcomes, enabling a more robust assessment of scenarios such as expanded subsidies or eligibility reforms.

Incorporating such methods would require additional data and modeling infrastructure, but this remains a promising direction for future work.

---

