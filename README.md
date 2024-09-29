# Canonical Correlation Analysis Between Regional Development and the Behavior of Rural Populations in West Java, Indonesia

## Project Overview
This project investigates the relationship between regional development and the characteristics of rural populations in West Java, Indonesia. It employs Canonical Correlation Analysis (CCA) to identify key factors within rural area community facilities and population characteristics that could help reduce poverty and improve rural development.

## Objectives
The study aims to:
- Analyze the relationship between rural area community facilities and population characteristics in West Java.
- Determine which variables from these categories can serve as key indicators to reduce poverty in rural areas.

## Methodology
**Data Collection**

The data used in this study were sourced from multiple open dataset websites and include 28 districts or cities in West Java. The data collected are divided into two categories:
1. **Rural Area Community Facilities:**
    - Number of Schools (NoS)
    - Number of Health Services (NoHS1, NoHS2, NoHS3)
    - Community Settlements (CS1, CS2, CS3)
    - Amount of Public Transportation (APB)
2. **Rural Population Characteristics:**
    - Percentage of People Living in Poverty (PPLP)
    - Number of Outmigrations (NoOut)
    - Literacy Rate (LR)

**Software and Tools**

The project is conducted using RStudio with the following R packages:
- `expm`
- `MASS`
- `readxl`
- `dplyr`
- `mvShapiroTest`
- `car`
- `tidyr`
- `purrr`
- `GGally`
- `CCA`
- `CCP`
  

**Analysis**

The Canonical Correlation Analysis (CCA) was employed to determine the strength of relationships between the sets of variables. Additionally, various statistical tests such as Shapiro-Wilk for normality and Variance Inflation Factor (VIF) for multicollinearity were conducted.

## Results
The analysis reveals:
- The number of schools and integrated health services has a significant impact on rural population characteristics.
- Increased educational and healthcare facilities improve rural community characteristics, while outmigration negatively affects these facilities.

## Conclusion
The results of this study provide insights into the key factors that influence rural development. Strengthening education, healthcare, and transportation infrastructure in rural areas is crucial to reducing poverty and bridging the gap between rural and urban development.

## Contributors
2501971742 - Alisha Zahra Saadiya

2501975620 - Diva Nabila Henryka 

2540122716 - Reyza Farzan Rahmatsyah 
