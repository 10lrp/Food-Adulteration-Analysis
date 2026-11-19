# Food Adulteration Monitoring Dashboard

An Excel dashboard exploring **1,000 food adulteration cases recorded from January to June 2024**. The project focuses on identifying where adulteration cases are concentrated, which product categories carry the greatest high-health-risk burden, and what the recorded cases suggest for food safety monitoring priorities.

## Project Overview

Food adulteration can affect different products and carry different levels of health risk. Rather than looking at the total number of cases alone, this analysis breaks the records down by product, month, adulterant, severity, health risk, and enforcement action.

The dashboard was built entirely in **Microsoft Excel** using **IF functions, PivotTables, PivotCharts, and slicers**. The source dataset was already cleaned, so this project did not include a data-cleaning stage. The work focused on creating analysis scores, summarizing the data, and communicating the findings through a dashboard.

## Dashboard at a Glance

| Dashboard metric | Result |
|---|---:|
| Total adulteration cases | **1,000** |
| Severe cases | **32.1%** |
| High-health-risk cases | **32.5%** |
| Product recalls issued | **255** |

## Key Findings

- **Juice and chicken appeared most frequently among the adulterated products.** These products had the highest case counts in the product comparison, making them useful categories to prioritize for closer monitoring.
- **Meat and dairy accounted for the largest volumes of high-health-risk cases.** Their contribution makes both categories important targets for risk-based monitoring.
- **May recorded the highest number of cases** during the January–June period, with 196 cases.
- **Melamine was the leading adulterant shown for dairy products** in the dashboard breakdown.
- **Enforcement actions were relatively consistent across severity levels** in the comparison of fines, product recalls, investigations, and warnings.

These findings describe patterns in the dataset; they should not be interpreted as estimates of food adulteration prevalence across the wider food supply.

## Methodology

### 1. Score creation with Excel IF functions

The dataset was provided in a cleaned format. I used Excel `IF` functions to create scoring fields for:

- **Severity Score** — to represent the severity level of each case.
- **Product Recall Score** — to represent the product-recall status or action.
- **Health Risk Score** — to represent the health-risk classification of each case.

These fields made it possible to summarize and compare cases consistently in the dashboard. The scoring rules and thresholds are not reproduced here because they are specific to the workbook.

### 2. Data summarization with PivotTables

I used PivotTables to aggregate the records and explore patterns across key dimensions, including:

- Cases by month.
- Adulterated products by frequency.
- High-health-risk cases by product category.
- Enforcement actions across severity levels.
- Adulterants across product categories, including dairy products.

### 3. Dashboard development

The summaries were presented through PivotCharts and KPI cards. Slicers were added to make it easier to explore the dashboard by **health risk, month, and severity** without changing the underlying analysis.

## Data Storytelling & Visualization Approach

A key design decision was to use **insight-led chart headlines instead of generic chart titles**.

Rather than simply naming a chart *“Cases by Month”*, the headline communicates the main takeaway—for example, **“May Marks the Peak in Adulteration Cases This Semester.”** This helps the audience understand the point of each visualization before interpreting the individual values.

The dashboard follows three storytelling principles:

1. **Lead with the takeaway.** Chart headlines highlight the most important pattern or comparison.
2. **Make priorities visible.** KPI cards and focused comparisons draw attention to severe cases, high-health-risk cases, recalls, and product categories with larger risk burdens.
3. **Support exploration.** Slicers allow the audience to examine the findings from different filters while keeping the dashboard in one place.

The goal was not only to display the data, but to guide the audience toward the food safety issues that deserve closer attention.

## Tools & Excel Features

- **Microsoft Excel** — analysis and dashboard development.
- **IF function** — creation of severity, product-recall, and health-risk scores.
- **PivotTables** — data aggregation and comparison.
- **PivotCharts** — visual presentation of summarized results.
- **Slicers** — interactive filtering by health risk, month, and severity.

## Project Objective

To demonstrate how a structured dataset can be transformed into an interactive, insight-led dashboard that helps communicate food adulteration patterns and identify potential priorities for food safety monitoring.
