# Data to Action: Masterclass on Making Smart Decisions - Capstone Project

## Overview
This section of the repository contains my work for the **Capstone Project** of the **"Data to Action: Masterclass on Making Smart Decisions"** hosted by Excelerate, completed as of August 31, 2025. The capstone applies skills learned throughout the 3-day masterclass to a simulated retail business scenario for RetailX, a multi-region lifestyle retailer. Using the RetailX Sales Data, I cleaned the dataset, derived key insights, created visualizations, and formulated strategic recommendations to boost sales and reduce returns.

## Dashboard Overview
<table>
  <tr>
    <td><img src="https://github.com/Fouzia0298/Data-to-Action-Masterclass-on-Making-Smart-Decisions/blob/main/Images/Dashboard.PNG" alt="Certificate Thumbnail" width="500" height="300"></td>
  </tr>
</table>

## Capstone Project: Driving Decisions with RetailX Data

### Phase 1: Data Cleaning & Preparation
**Objective**: Clean and prepare the raw dataset for analysis by removing duplicates, correcting inconsistencies, standardizing formats, and handling missing or anomalous data.

**Description**: The raw dataset (RetailX_Sales_Data.xlsx) was processed to ensure quality. Steps included standardizing payment types (e.g., "Upi" to "UPI", "Credit C" to "Credit Card"), formatting dates, and verifying no missing values or duplicates. The cleaned dataset is provided in CSV format for easy access.

**Files**: 
- `RetailX_Sales_Data_Cleaned.csv` (dataset)

### Phase 2: Data Analysis & Insights
**Objective**: Analyze the cleaned data to answer strategic business questions, such as top-performing regions, return rates by category, average transaction revenue, and correlations between payment methods and returns.

**Description**: Key insights include:
- North Zone generated the highest revenue ($181,070 or $183,161 as per insights doc – slight variance noted).
- Electronics had the highest return rate (19-22.73%).
- Average revenue per transaction ≈ $5,431.14.
- Returns most associated with UPI and Debit Card (16%), none with Cash.
Interpretations suggest prioritizing North Zone, investigating Electronics returns, and benchmarking low-return areas.

**Files**: 
- `Project PPT` (Detailed insights and interpretations)
- `RetailX_Sales_Data_Dashboard.xlsm` (Summary pivots for revenue by region and return rates)
- `RetailX_Sales_Strategy.docs` (SWOT Analysis) 
### Phase 3: Visual Storytelling
**Objective**: Create compelling visuals to communicate trends and patterns clearly.

**Description**: Visuals include:
- Bar chart: Total revenue by region (North Zone highest, South Zone lowest).
- Pie chart: Percentage of returns by category (Electronics largest slice at ~22.73%, Apparel 0%).


### Phase 4: Strategic Recommendation
**Objective**: Use a decision-making framework (SWOT) to formulate data-backed recommendations for optimizing operations, profitability, and customer satisfaction.

**Description**: SWOT analysis highlights strengths (e.g., North Zone revenue, 0% Apparel returns), weaknesses (e.g., high Electronics returns), opportunities (e.g., expand Apparel in North Zone), and threats (e.g., eroding profitability from returns). Recommendation: Increase investment in Apparel in North Zone while investigating and mitigating returns for Electronics and digital payments.

**File**: `RetailX_Strategy.docx` (SWOT analysis and strategic recommendation with supporting data)

## Repository Structure
- `Project PPT.pdf`: Comprehensive overview of all phases.
- `RetailX_Sales_Data_Cleaned.csv`: Cleaned and prepared dataset.
- `RetailX_Sales_Data_Dashboard.csv`: Summary data for revenue and returns.
- `RetailX_Strategy_Fouzia_Ashfaq.docx`: Strategic recommendations with SWOT.

## Tools Used
- Microsoft Excel: For data cleaning, analysis (pivot tables), and dashboard creation.
- Microsoft Word: For documenting insights, visuals descriptions, and strategy.
- Data analysis techniques: Aggregation, percentage calculations, correlation identification.

## Key Learnings
- **Integrated Application**: Combining cleaning, analysis, visualization, and strategy demonstrates how data drives end-to-end decision-making.
- **Insight-Driven Strategy**: High return rates in specific categories and payments highlight areas for targeted improvements to enhance profitability.
- **Regional Focus**: Identifying top regions like North Zone allows for resource optimization and growth scaling.
- **Framework Utility**: SWOT effectively translates data insights into actionable business recommendations.

## Additional Insights and Charts
To further enhance the capstone, consider the following insights and chart suggestions based on the RetailX Sales Data:

### Additional Insights
- **Sales Trends Over Time**: Analyze daily or weekly sales trends to identify peak sales periods (e.g., weekends vs. weekdays) and seasonal patterns within the July 2024 data.
- **Product Performance by Store**: Evaluate which stores (e.g., Store 101, 102) perform best for specific categories (e.g., Electronics vs. Fitness) to optimize inventory allocation.
- **Payment Method Revenue Contribution**: Assess the revenue contribution of each payment type (Cash, Debit Card, Credit Card, UPI) to determine if certain methods correlate with higher sales volumes.
- **Return Impact on Revenue**: Quantify the revenue lost due to returns (e.g., Electronics returns reduced revenue by ~$10,000) to prioritize mitigation efforts.

### Suggested Charts
- **Line Chart: Sales Trends Over Time**
  - **Description**: Plot daily total revenue from July 1 to July 25, 2024, to identify trends or spikes.
  - **Purpose**: Highlights peak sales days (e.g., July 3 with $64,987 from Smartwatch) for targeted promotions.
- **Bar Chart: Revenue by Store and Category**
  - **Description**: Compare revenue contributions of each store (101, 102, 103, 104) across categories (Apparel, Electronics, Fitness).
  - **Purpose**: Identifies top-performing stores per category (e.g., Store 101 for Fitness).
- **Pie Chart: Revenue by Payment Type**
  - **Description**: Show the proportion of total revenue from Cash, Debit Card, Credit Card, and UPI.
  - **Purpose**: Reveals if Cash (0% returns) drives significant revenue, justifying process enhancements for digital payments.
- **Bar Chart: Revenue Loss from Returns by Category**
  - **Description**: Display the total revenue lost due to returns for Electronics, Fitness, and Apparel.
  - **Purpose**: Quantifies the financial impact (e.g., Electronics returns) to support investment in quality control.

These can be created using the cleaned dataset and added to `RetailX_Visuals_Fouzia_Ashfaq.docx` with updated descriptions.

This capstone culminates the masterclass, showcasing a data-first mindset for real-world retail challenges, finalized on August 31, 2025.
