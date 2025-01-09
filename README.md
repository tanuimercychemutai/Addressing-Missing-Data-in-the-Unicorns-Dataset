# Addressing Missing Data in the Unicorns dataset

## 📚 Introduction

Handling missing data is a critical step in cleaning and preparing datasets for meaningful insights, especially during **Exploratory Data Analysis (EDA)**. 

In this project, you’ll step into the role of a **financial data consultant** tasked with helping an investor identify new business opportunities. The goal is to provide insights into profitable companies (often referred to as "unicorns") valued at over $1 billion, based on specific criteria.

---

## 🔂 Project Overview

The investor has requested the following deliverables:

1. **Hardware Industry Insights**  
   - List of companies in the hardware industry based in:
     - Beijing  
     - San Francisco  
     - London  

2. **Artificial Intelligence Industry Insights**  
   - Companies in the artificial intelligence (AI) industry based in London.

3. **Top 20 Countries by Valuation**  
   - List of the top 20 countries sorted by the **sum of company valuations**, excluding:  
     - United States  
     - China  
     - India  
     - United Kingdom  

4. **Global Valuation Map (Post-2020)**  
   - A global map of company valuations for countries with businesses that joined the unicorn list after 2020.

5. **Global Valuation Map (Exclusions Applied)**  
   - A global map of company valuations, excluding:
     - United States  
     - China  
     - India  
     - United Kingdom  
   - **Special Requirement**: A separate map for Europe.

---

## 💡 Objectives

- **Understand and Address Missing Data**:  
  The dataset includes a variety of business-related data points, such as:
  - Year Founded  
  - Industry  
  - City  
  - Country  
  - Continent  
  - Valuation  
  Missing values in these columns will be identified and addressed to ensure accurate results.

- **Explore and Visualize Insights**:  
  By addressing missing data, the cleaned dataset will be used to produce lists, rankings, and visualizations that meet the client's requirements.

---

## 🛠️ Tools & Libraries

- **Python**  
  - `pandas` for data cleaning and manipulation  
  - `matplotlib` and `seaborn` for data visualization  
  - `geopandas` for mapping global valuations  
- **Jupyter Notebook** (or IDE of your choice)

---

## 📊 Key Steps in the Workflow

1. **Data Cleaning**  
   - Identify and address missing values.
   - Validate data for consistency and completeness.

2. **Subset Creation**  
   - Filter data based on the specified industries, cities, and countries.

3. **Ranking and Aggregation**  
   - Aggregate valuations by country and rank them to produce the required top 20 list.

4. **Data Visualization**  
   - Create global maps highlighting company valuations based on the provided criteria.
   - Generate a separate map for Europe.

---

 ## ✨ Key Learnings

- Addressing missing data to improve data quality.
- Subsetting data based on specific client needs.
- Visualizing insights through maps and aggregated rankings.

---
