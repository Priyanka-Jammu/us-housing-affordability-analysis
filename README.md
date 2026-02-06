# U.S. Housing Affordability Analysis (2015–2023)

## Project Overview
This project analyzes housing affordability trends across all 50 U.S. states from 2015 to 2023 by integrating housing market data with economic, demographic, population, and risk indicators. The analysis focuses on understanding how rising home prices, rental costs, income levels, mortgage rates, migration, and socioeconomic stress factors impact affordability across regions.

The insights are presented through interactive Tableau dashboards designed for state- and region-level comparison.

---

## Key Research Questions
1. How have home prices and rental rates changed over time in the U.S.?
2. Which states are the most and least affordable for homeownership and renting?
3. How do income levels, mortgage rates, and socioeconomic stress indicators impact affordability?
4. How does population growth or migration affect housing prices and access?
5. How do economic structure, demographics, and disaster risk shape housing affordability?

---

## Data Sources
This project uses publicly available datasets from the following sources:

- **Zillow (ZHVI & ZORI):** State-level home values and rental rates  
- **U.S. Census Bureau (ACS DP03 & DP05):** Income, poverty, employment, insurance, and demographic indicators  
- **Census Population Estimates Program (PEP):** Population size and migration trends  
- **Bureau of Labor Statistics (BLS):** Employment statistics  
- **Bureau of Economic Analysis (BEA):** State-level GDP  
- **FEMA National Risk Index (NRI):** Disaster risk and vulnerability indicators  
- **FRED:** National 30-year fixed mortgage rates  
- **Kaggle:** U.S. state-to-region mapping  

> **Note:** Raw datasets are not included in this repository due to file size, licensing, and the use of publicly accessible sources. All data can be re-created by downloading directly from the links above.

---

## Data Integration & Modeling
- Cleaned and standardized multiple datasets to a **State–Year** level
- Combined Zillow home value and rental datasets into a unified housing table
- Merged Census economic and demographic indicators
- Joined FEMA risk data at the state level
- Applied regional grouping (Northeast, Midwest, South, West)
- Used Tableau relationships for flexible filtering and drill-down analysis

---

## Key Metrics & Indicators
- Cost to Buy vs. Cost to Rent
- Home Value-to-Income Ratio
- Rent Affordability Index
- Overall Housing Affordability Index
- Employment-to-Population Ratio
- Home Price-to-GDP Ratio
- Agricultural Value per Capita
- Year-over-Year Home Value & Mortgage Rate Changes
- Disaster Risk Exposure
- Demographic Comparisons (age, race, gender, population)

---

## Tableau Dashboards & Analysis
The Tableau dashboards explore:
- Long-term trends in buying vs. renting costs
- State and regional affordability disparities
- Top and bottom affordability states
- Impact of mortgage rate changes
- Socioeconomic stress overlays (poverty, unemployment, insurance gaps)
- Migration patterns and commute-time effects
- Economic structure and disaster risk comparisons

---

## Key Insights
- Home-buying costs have increased faster than rental costs since 2021
- Mortgage rate spikes significantly worsened affordability even when price growth slowed
- The West and Northeast consistently show higher affordability stress
- Affordable states do not always experience positive net migration
- Population size, economic structure, and disaster risk add hidden pressure to housing markets
- Housing affordability is shaped by interacting economic, demographic, and risk factors

---

## Tools & Technologies
- **Tableau** – Data modeling, relationships, and interactive dashboards  
- **Excel / CSV** – Data cleaning and validation  
- **Public APIs & Open Data Sources** – Census, BLS, BEA, FRED, FEMA  

---

## Reproducibility
All datasets used in this project are publicly available. The analysis can be reproduced by re-downloading the data from the listed sources and applying the same state–year joins and calculated metrics described in the report.

---

## Author
**Priyanka Jammu**  
Graduate Student – Artificial Intelligence & Business Analytics  
University of South Florida
