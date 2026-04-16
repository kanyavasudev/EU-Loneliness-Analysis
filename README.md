# EU Loneliness Survey Analysis

## Project Overview
This project analyzes loneliness patterns across Europe using data from the **EU Loneliness Survey 2022**. The goal is to identify how demographic, lifestyle, and behavioral factors influence loneliness levels.

---

## Dataset Information

- **Source:** EU Loneliness Survey 2022  
- **Conducted by:** Joint Research Centre (JRC), European Commission  
- **Sample Size:** 25,646 respondents  
- **Coverage:** 27 EU countries  
- **Target Population:** Individuals aged 16+  
- **Method:** Online survey (Nov–Dec 2022)  

🔗 Dataset Link:  
https://data.jrc.ec.europa.eu/dataset/82e60986-9987-4610-ab4a-84f0f5a9193b

---

## Project Objective

To explore:
- Who experiences the highest levels of loneliness  
- How work, income, and lifestyle impact loneliness  
- The relationship between social media usage and loneliness  
- Differences across demographic groups  

---

## Tools & Technologies

- **Python (Pandas)** → Data cleaning & preprocessing  
- **Power BI** → Data visualization & dashboard  
- **Excel** → Dataset handling  

---

## Data Preparation

- Selected relevant columns from the original dataset  
- Retained missing values (handled during visualization stage)  
- Converted encoded survey values into readable labels  
- Created new features:
  - **Generation (Age Groups)**
  - **Income Range**
  - **Social Media Usage Categories**
- Checked for duplicates and ensured data consistency  

---

## Dashboard Features

The Power BI dashboard includes:

- **KPI Summary**
  - Average Loneliness Index
  - Loneliest Group, Generation, and Relationship Type

- **Demographic Analysis**
  - Loneliness by Generation, Relationship, and Country

- **Work & Income Analysis**
  - Loneliness by Work Status, Income Range, Work Mode

- **Health & Lifestyle Analysis**
  - Impact of health conditions, life events, and pet ownership

- **Social Media Analysis**
  - Usage frequency vs loneliness
  - Purpose of usage vs loneliness
  - Trends across generations

- **Occupation & Social Factors**
  - Loneliness by occupation and sexual orientation

- **Interactive Filters**
  - Country, Gender, Generation

---

## Key Insights

- **Gen Z** reports the highest loneliness levels  
- **Students** are the most affected group  
- **Remote workers** show higher loneliness than office workers  
- **Higher social media usage** is associated with increased loneliness  
- Using social media as a **replacement for face-to-face interaction** shows the strongest link to loneliness  
- **Health conditions and major life events** slightly increase loneliness  
- **Low-income groups** report higher loneliness compared to high-income groups  

---

## Limitations

- Self-reported data may introduce bias  
- Correlation does not imply causation  
- Dataset limited to European population  
- Cross-sectional data (no time-based tracking)  
- Income data is self-reported  

---
## Folder Structure

- `datasets/original_dataset/` — Raw EU loneliness survey data (source file)

- `datasets/cleaned_dataset/` — Processed datasets used for analysis and visualization  
  - `loneliness_clean_python.csv` — Cleaned dataset from Python preprocessing  
  - `loneliness_related_dataset.xlsx` — Refined dataset for Power BI  
- `loneliness_analysis_Python.ipynb` — Data cleaning, transformation, and analysis using Python  
- `loneliness_analysis_powerbi.pbix` — Power BI dashboard file  
- `dashboard_analysis.pdf` — Exported dashboard preview  
- `README.md` — Project documentation  
---

## Files Included

- `loneliness_analysis_Python.ipynb` → Data cleaning & analysis  
- `loneliness_analysis_powerbi.pbix` → Power BI dashboard file  
- `dashboard_analysis.pdf` → Dashboard preview  
- `datasets/` → Original and cleaned datasets  

---

## Conclusion

This project highlights how loneliness is influenced by a combination of demographic, behavioral, and lifestyle factors. 
It provides insights into how modern patterns such as remote work and social media usage contribute to loneliness across populations.
