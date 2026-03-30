# 📊 COVID-19 Data Analysis Project

This project performs an end-to-end analysis of global COVID-19 data to understand trends in confirmed cases, deaths, and recoveries across countries from Jan 2020 to May 2021.

## 🚀 Objectives
* Analyze pandemic progression across countries
* Identify peak waves, death rates, and recovery patterns
* Generate insights to understand severity and healthcare impact

## 📂 Datasets
* Confirmed cases
* Deaths
* Recoveries

### Each dataset contains:
* Country/Region, Province/State
* Latitude & Longitude
* Daily cumulative data

## ⚙️ Data Processing
* Converted wide-format data to long format using pd.melt()
* Merged datasets into a unified dataframe
* Created features:
    * Daily cases (diff)
    * Monthly aggregation (YearMonth)
* Calculated:
    * Death Rate = Deaths / Confirmed
    * Recovery Ratio = Recovered / Confirmed
  
## 📈 Key Analyses
* Time-series analysis of cases and deaths (US, Italy, Brazil)
* Identification of multiple pandemic waves
* Comparison of top death rate regions (e.g., Yemen, MS Zaandam, Mexico)
* Recovery vs death comparison (e.g., South Africa)
* Monthly recovery ratio trends (US, India)

## 📊 Visualizations
* Line plots for trends and waves
* Bar charts for comparisons and rankings
* Highlighted peaks, ratios, and regional differences

## 🧠 Key Insights
* Pandemic followed distinct wave patterns globally
* Death rates varied significantly due to healthcare and testing differences
* Recoveries improved over time with better treatment
* Recovery ratios dropped during major surge waves

## 🎯 Conclusion

This project demonstrates end-to-end data analysis, including data cleaning, transformation, feature engineering, and visualization, to extract meaningful insights from real-world pandemic data.
