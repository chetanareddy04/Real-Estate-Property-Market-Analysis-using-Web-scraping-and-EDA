#  Real Estate Property Market Analysis – Hyderabad

##  Project Overview

A **Web Scraping + Exploratory Data Analysis (EDA)** project focused on analysing residential flat listings in Hyderabad collected from MagicBricks.

Using Python and Selenium, property data was collected and analysed to understand pricing patterns, property characteristics, and locality-wise variations in Hyderabad's residential real estate market.

##  Business Problem

Hyderabad's growing real estate market offers properties across different localities, sizes, and price ranges. Comparing these listings and understanding their pricing patterns can be challenging for prospective buyers.

This project analyses real-world property listings to uncover meaningful market trends, compare locality-wise prices, and understand relationships between property characteristics.

##  Project Objectives

- Collect real-world residential property data from MagicBricks using web scraping.
- Analyse property pricing patterns and locality-wise variations.
- Explore relationships between property characteristics and prices.
- Apply statistical analysis to derive meaningful market insights.

##  Data Source

- **Platform:** [MagicBricks – Flats for Sale in Hyderabad](https://www.magicbricks.com/flats-in-hyderabad-for-sale-pppfs)
- **Location:** Hyderabad, Telangana
- **Property Category:** Residential Flats for Sale
- **Collection Method:** Web Scraping using Python and Selenium
- **Final Dataset:** 1,263 records × 10 features

##  Project Workflow & Analysis

1. **Web Scraping & Data Collection** – Extracted residential property listings from MagicBricks using Python and Selenium.

2. **Data Understanding** – Examined dataset structure, features, data types, and basic statistics.

3. **Data Cleaning & Preparation** – Handled missing values, inconsistencies, and prepared the dataset for analysis.

4. **Univariate Analysis** – Explored individual features such as BHK distribution, furnishing status, property area, and prices.

5. **Bivariate Analysis** – Investigated relationships between property features, including area vs. price and BHK vs. price.

6. **Multivariate Analysis** – Examined relationships among multiple numerical features using correlation analysis and a heatmap.

7. **Statistical Hypothesis Testing**

   Welch's t-test: Compared mean price per square foot between 2-BHK and 3-BHK properties.

   One-Way ANOVA: Examined differences in average property prices across the top 10 localities

8. **Insights & Conclusion** – Summarised key findings and statistical results to understand Hyderabad's residential property market.

##  Key Findings

- 3-BHK properties represented the largest share of collected listings.
- Most properties had an area between 1,000 and 2,000 sq. ft.
- Unfurnished properties formed the largest furnishing category among listings with furnishing information.
- Kokapet recorded the highest average listing price among the selected localities.
- Total price and price per square foot showed a very strong positive correlation.

##  Tools & Technologies

- **Programming Language:** Python
- **Web Scraping:** Selenium
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** SciPy
- **Environment:** Jupyter Notebook / Anaconda



