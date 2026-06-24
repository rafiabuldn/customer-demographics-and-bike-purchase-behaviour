# Customer Demographics and Bike Purchase Behaviour

**Tool:** Microsoft Excel | **Dataset:** 1,026 customer records | **Regions:** North America, Europe, Pacific

## Overview

An interactive Excel dashboard analysing what drives bike purchasing decisions across 1,026 customers in three global regions. The project involved data cleaning, age bracket categorisation using formulas, and building a fully interactive dashboard using Pivot Tables, Pivot Charts, and slicers.

![Dashboard Preview](dashboard_screenshot.png)
Figure 01: Interactive Dashboard

![Pivot Preview](pivot_screenshot.png)
Figure 02: Pivot Tables and Charts

![Data Preview](data_screenshot.png)
Figure 03: Cleaned Working Data

## Dataset

1,026 customer records across 13 variables including gender, income, age, marital status, education, occupation, number of cars, commute distance, region, and bike purchase outcome.

| Region | Customers | Share |
|---|---|---|
| North America | 508 | 50% |
| Europe | 318 | 31% |
| Pacific | 200 | 20% |

## Key Insights

### 1. Income influences purchase decisions

Higher earners were more likely to purchase a bike across both genders.

| Gender | Buyers Avg Income | Non-Buyers Avg Income |
|---|---|---|
| Male | £59,603 | £56,520 |
| Female | £55,267 | £53,450 |

### 2. Middle-aged customers dominate purchases

61% of all bike purchases were made by customers aged 31 to 54. Adolescents (under 31) accounted for 14% and older customers (55+) made up 25% of purchases.

### 3. Commute distance is a strong predictor

Customers commuting 0 to 1 miles had the highest purchase rate at 207 buyers vs 171 non-buyers. Purchase likelihood dropped sharply at 10+ miles, with only 33 buyers compared to 80 non-buyers. Short-distance commuters represent the most promising target segment.

### 4. Single customers purchase more than married customers

| Marital Status | Purchased | Purchase Rate |
|---|---|---|
| Single | 259 | 54% |
| Married | 236 | 43% |

### 5. North America is the largest market

North America accounts for nearly half of all customers in the dataset at 508 of 1,026. Europe and the Pacific represent the remaining share and are fully represented in the dashboard analysis.

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
| `data.xlsx` | Working Sheet | Cleaned raw data with age bracket formula |
| `README.md` | | Project documentation |

## Skills Demonstrated

`Microsoft Excel` `Pivot Tables` `Data Visualisation` `Dashboard Design` `Data Cleaning` `Exploratory Data Analysis`

## Author
Rafi Abu | BSc Computing Systems, Ulster University
