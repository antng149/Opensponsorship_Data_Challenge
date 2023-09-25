# OpenSponsorship Data Analytics Challenge

## Table of Contents
- [Brand Engagement Deep Dive](#brand-engagement-deep-dive)
- [Campaign Onboarding Analysis](#campaign-onboarding-analysis)
- [User Search Behavior Insights](#user-search-behavior-insights)

---

## Deliverable 1 - Brand Engagement Deep Dive

### Introduction
This analysis focuses on OpenSponsorship brand data, with the primary objective of uncovering patterns and factors influencing customer subscriptions.

### Data Loading and Preprocessing
- Data is loaded from an Excel file.
- Preprocessing includes calculating active durations and cleaning roles.
- Significant missing values in 'bantScore' and 'companySize' fields are noted.

### Exploratory Data Analysis (EDA)
- Analysis of the 'planLevel' field to gauge how many brands have upgraded their subscriptions.
- Distribution checks for categorical variables like 'role', 'industry_categories', 'companySize', and 'country'.
- Calculation of the active duration for brands.

### Analysis of Active Duration
- A histogram shows the distribution of 'active_duration'.
- A boxplot provides insights into 'active_duration' distribution across different plan levels.

---

## Deliverable 2 - Campaign Onboarding Analysis

### Introduction
This analysis delves into brand campaigns to comprehend how brands interact with their campaign publishing activities. The analysis revolves around several key questions:
1. The proportion of brands that published campaigns versus those that didn't, categorized by plan level.
2. The number of brands that continued to create campaigns after publishing their first.
3. Brands with the most significant campaign budgets.
4. The duration taken by new brands to publish a campaign.

### Data Preprocessing
- Two primary datasets, 'campaigns data' and 'users data', are loaded.
- Relevant information like the budget for each campaign is extracted from the `payment` column in the campaign data.

### Analysis: Brands with Multiple Campaigns
- A comprehensive look is taken at brands that have published more than one campaign.
- The top 5 brands with the highest total campaign budgets are identified.

### Analysis: Time to First Campaign
- The primary objective is to determine the average time new brands take to publish a campaign.
- The average time to first campaign is then calculated, revealing that on average, it takes about 54 days for new brands to release a campaign.

---

## Deliverable 3 - User Search Behavior Insights

### Introduction
The focus of this analysis is on the search trends exhibited by users across different plan levels. Emphasis is placed on understanding and contrasting the behaviors of users on Plan Levels 0 and 3.

### Data Loading and Preprocessing
- Datasets pertaining to user search activities are loaded.
- Data preprocessing steps are performed.

### Analysis of Search Trends for Plan Levels 0 and 3
- A line plot visualizes search trends for Plan Levels 0 and 3 over a two-month period.

### Day-over-Day Growth in Search Counts
- The rate of change in search activity, represented as the day-over-day growth rate, is calculated for each plan level.

### Visualization and Observations on Day-over-Day Growth Rates
- The growth rates for Plan Levels 0 and 3 are visualized, revealing distinct patterns.
