# Customer Demographics and Bike Purchase Behaviour

**Tool:** Microsoft Excel | **Raw Dataset:** 1,026 records | **Clean Dataset:** 1,000 records | **Regions:** North America, Europe, Pacific

## Overview

An interactive Excel dashboard identifying what drives bike purchasing decisions across 1,000 customers in three global regions. The project covers the full analyst workflow: raw data cleaning, age bracket categorisation using nested IF formulas, pivot table analysis, and an interactive dashboard with slicers and charts.

![Dashboard Preview](dashboard_screenshot.png)
Figure 01: Interactive Dashboard

![Pivot Preview](pivot_screenshot.png)
Figure 02: Pivot Tables and Charts

![Data Preview](data_screenshot.png)
Figure 03: Cleaned Working Data

## Dataset

The raw dataset contained 1,026 customer records. After cleaning, 1,000 records were retained across 13 variables: gender, income, age, marital status, education, occupation, number of cars, commute distance, region, and bike purchase outcome.

| Region | Customers | Share |
|---|---|---|
| North America | 508 | 51% |
| Europe | 300 | 30% |
| Pacific | 192 | 19% |

## Key Insights

### 1. Income influences purchase decisions

Higher earners were more likely to purchase a bike across both genders.

| Gender | Buyers Avg Income | Non-Buyers Avg Income |
|---|---|---|
| Male | £60,124 | £56,208 |
| Female | £55,774 | £53,440 |

### 2. Middle-aged customers dominate purchases

80% of all bike purchases were made by customers aged 31 to 54. Older customers (55+) accounted for 12% and adolescents (under 31) made up 8% of purchases. Middle-aged customers are the core buying segment and the primary audience for any marketing activity.

### 3. Commute distance is a strong predictor

Customers commuting 0 to 1 miles had the highest purchase volume at 200 buyers. Purchase likelihood dropped sharply beyond 5 miles, with only 33 buyers at 10+ miles compared to 78 non-buyers. Short-distance commuters are the most commercially viable target segment.

### 4. Single customers purchase more than married customers

| Marital Status | Purchased | Purchase Rate |
|---|---|---|
| Single | 250 | 54% |
| Married | 231 | 43% |

Single customers converted at a notably higher rate, suggesting lifestyle and disposable income may be stronger drivers than marital status alone.

### 5. North America is the largest market

North America accounts for 51% of the clean dataset at 508 customers. Europe and Pacific represent 30% and 19% respectively. All three regions are filterable via the dashboard slicers.

## Dashboard Features

The dashboard includes 3 interactive slicers allowing simultaneous filtering by Region, Marital Status, and Education. Visualisations include a bar chart showing average income by gender and purchase outcome, a pie chart showing age group distribution of buyers, and a line chart comparing commute distance against purchase behaviour.

## How to Use

1. Download and open `data.xlsx`
2. Navigate to the **Dashboard** tab
3. Use the slicers on the left to filter by Region, Marital Status, or Education
4. Charts update automatically based on your selection

## Repository Structure

| File | Tab | Description |
|---|---|---|
| `data.xlsx` | Dashboard | Interactive charts and slicers |
| `data.xlsx` | Pivot Table | Underlying pivot tables and charts |
| `data.xlsx` | Working Sheet | Cleaned data with age bracket formula |
| `README.md` | | Project documentation |

## Skills Demonstrated

`Microsoft Excel` `Pivot Tables` `Data Visualisation` `Dashboard Design` `Data Cleaning` `Exploratory Data Analysis`


## Author
Rafi Abu | BSc Computing Systems, Ulster University
