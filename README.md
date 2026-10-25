#  EazyDiner Restaurant Data Analysis

##  Project Overview

This project focuses on collecting restaurant data from EazyDiner across seven major Indian cities using Python web scraping techniques. The extracted data is cleaned, processed, and analyzed to understand restaurant distribution, cuisine popularity, pricing patterns, and location-wise variations.

The project demonstrates how web scraping and Exploratory Data Analysis (EDA) can transform raw restaurant data into meaningful business insights.

##  Project Objective

The objective of this project is to collect restaurant data from EazyDiner using Python web scraping techniques and transform the extracted information into a structured dataset for analysis. The project aims to perform data cleaning, feature engineering, Exploratory Data Analysis (EDA), and data visualization to identify restaurant trends and generate actionable business insights.

##  Business Problem

The restaurant industry is highly competitive, and understanding restaurant distribution, cuisine preferences, and pricing patterns can help businesses make informed decisions.

This project explores the following questions:

- Which cities have the highest number of restaurants in the collected dataset?
- Which cuisines appear most frequently?
- Which restaurants have the highest cost for two?
- How does the average restaurant cost vary across cities?
- Which restaurant locations have a higher concentration of listings?
- How can restaurants be categorized according to dining costs?
- Are there unusually high or low restaurant costs in the dataset?

##  Cities Covered

The data collection covers seven major Indian cities:

- Delhi NCR
- Mumbai
- Bengaluru
- Hyderabad
- Chennai
- Kolkata
- Pune

##  Dataset Overview

The dataset contains restaurant information collected from EazyDiner.

| Column Name | Description |
|---|---|
| `Restaurant_Name` | Name of the restaurant |
| `City` | City where the restaurant is listed |
| `Cuisine` | Cuisine type or category |
| `Restaurant_Location` | Restaurant's listed locality |
| `Cost_For_Two` | Estimated dining cost for two people |


##  Project Workflow

1. **Data Collection:** Extract restaurant information from EazyDiner using Python web scraping.
2. **Data Extraction:** Retrieve restaurant names, cities, cuisines, locations, and cost information.
3. **Data Cleaning:** Handle missing values, remove duplicate records, and prepare columns for analysis.
4. **Data Transformation:** Convert extracted cost values into an appropriate numeric format.
5. **Feature Engineering:** Create cost categories such as Budget, Mid Range, Premium, and Luxury.
6. **Exploratory Data Analysis:** Analyze restaurant distribution, cuisine frequency, and pricing patterns.
7. **Data Visualization:** Create charts to communicate important patterns and comparisons.
8. **Business Insights:** Interpret the results and develop business recommendations.
9. **Dataset Export:** Save the cleaned dataset for future analysis and reuse.

##  Tools and Technologies

- **Python** – Programming language
- **Requests** – Sending HTTP requests to retrieve web pages
- **BeautifulSoup** – Parsing HTML and extracting restaurant information
- **Pandas** – Data cleaning, manipulation, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Interactive coding and analysis
- **GitHub** – Project version control and sharing

## Exploratory Data Analysis (EDA)

### 1. City-wise Restaurant Distribution

Analyzes the number and proportion of restaurants collected from each city to understand differences in dataset coverage.

### 2. Cuisine Popularity Analysis

Identifies frequently listed cuisines to understand the cuisine categories most represented in the collected data.

### 3. Restaurant Cost Distribution

Uses histograms and descriptive statistics to examine dining costs and understand price variation.

### 4. Top Most Expensive Restaurants

Identifies the ten restaurants with the highest recorded cost for two.

### 5. City-wise Pricing Comparison

Compares average restaurant costs across cities to explore differences in listed dining prices.

### 6. Restaurant Location Analysis

Examines restaurant listings by locality to identify areas with more restaurants represented in the dataset.

### 7. Restaurant Cost Category Analysis

Groups restaurants into Budget, Mid Range, Premium, and Luxury categories based on their cost for two.

### 8. Cost Outlier Analysis

Uses boxplots to identify unusually high or low dining costs that may represent premium restaurants or require further validation.

## Key Business Insights

The analysis can help identify:

- Cities with higher or lower restaurant representation in the collected dataset.
- The most frequently listed cuisine categories.
- Differences in dining costs across cities.
- Restaurants positioned at the higher end of the price range.
- Localities with a greater concentration of restaurant listings.
- The distribution of restaurants across different cost categories.
- Potential pricing anomalies that warrant further investigation.


## Business Recommendations

- **Pricing Strategy:** Compare restaurant costs to understand relative price positioning among listed restaurants.
- **Cuisine Planning:** Use cuisine frequency patterns to explore popular categories and potential opportunities for differentiation.
- **Market Research:** Investigate cities and localities with lower restaurant representation to assess possible expansion opportunities.
- **Customer Segmentation:** Use cost categories to compare dining options for different budgets.
- **Premium Positioning:** Study high-cost restaurant listings to understand the premium segment.
- **Data Quality Improvement:** Validate missing or unusual cost values to improve the reliability of future analysis.


##  Business Value

This project demonstrates how restaurant data collected through web scraping can be converted into useful information for market research and pricing analysis.

The findings can support:

- Restaurant market research
- Pricing comparisons
- Cuisine trend exploration
- Location-based analysis
- Restaurant category segmentation
- Data-driven business decision-making

##  Project Structure

```text
EazyDiner-Restaurant-Data-Analysis/
│
├── EazyDiner_Restaurant_Analysis.ipynb
├── eazydiner_multiple_cities.csv
├── README.md
└── requirements.txt
```




##  Limitations

- The dataset represents restaurants successfully collected from EazyDiner, not necessarily every restaurant in each city.
- Website pagination and page structure may affect the number of records collected.
- Some restaurant details or cost values may be missing.
- Listed costs are estimates and may change over time.
- Business conclusions are limited to the available data and should not be treated as definitive market-wide findings.

##  Conclusion

This project demonstrates an end-to-end data analytics workflow, from web scraping and data preprocessing to exploratory analysis, visualization, and business recommendations.

By analyzing restaurant listings across seven major Indian cities, the project explores cuisine popularity, restaurant distribution, and dining cost patterns. It also demonstrates practical skills in Python programming, web scraping, data manipulation, feature engineering, and data visualization.

Overall, the project highlights how Python-based data analytics can transform raw restaurant information into meaningful insights for restaurant market research and business decision-making.


**Project:** EazyDiner Restaurant Data Analysis

**Domain:** Python | Web Scraping | Exploratory Data Analysis | Data Visualization
