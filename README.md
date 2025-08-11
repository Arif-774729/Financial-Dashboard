# Power BI Personal Finance Dashboard

A dynamic and interactive Power BI dashboard designed to monitor personal financial health over time. It provides insightful visualizations on income, expenses, savings, and net worth (all segmented by category) and tracked monthly.

## Dashboard Overview

### Top Summary Cards (Dynamic)

- **Total Income**: ₹2.15M  
- **Expense %**: 68.1%  
- **Savings %**: 32.1%  
- **Total Net Worth**: ₹690.38K  
  _Hover tooltip:_ Shows a **line chart** of **monthly net worth growth**.

These cards are **interactive with the date filter** and update based on the selected period.

### Static All-Time Cards

Below the dynamic cards are the all-time stats (not affected by the date filter):

- **All-time Income**
- **All-time Expense %**
- **All-time Savings %**
- **All-time Net Worth**

These provide a **lifetime financial snapshot** regardless of selected filters.

### Date Filter

Interactive **Year-Month slicer** for temporal analysis:

- Filter data from **2018 to 2021**
- Dynamically updates charts, cards, and matrices across the dashboard

### Spending Breakdown (Bar Chart)

- Displays **expense components** (e.g., House Rent, Groceries, EMIs)
- Hover over any bar to view a **tooltip line chart** of **monthly trends** for that category
- Shows the **% share** of each expense (e.g., House Rent – 32.67%)

### Savings Breakdown (Bar Chart)

- Visualizes **savings allocations** (e.g., Mutual Funds, PPF, Liquid Cash)
- Shows the **% share** of each savings type
- Tooltips include a **line chart of monthly contributions** for each category

### Monthly Financial Performance (Line Chart)

Tracks:

- **% Income change MoM** (Blue Line)
- **Monthly Expense %** (Red Line)
- **Savings %** (Green Line)
- **Target Savings %** (Black dotted line)

Useful for spotting trends, seasonal patterns, and savings performance.

### Detailed Statement (Matrix Table)

- Year-wise breakdown from 2018 to 2021 by **type** and **category**
- Interactive: clicking a row filters the entire dashboard
- Totals for annual income, expenses, and savings

## Features

- Time Slicer (Year & Month)
- Dynamic Interactions (cross-filtering visuals)
- Tooltip Charts for granular insights
- Auto-calculated metrics (Expense %, Savings %, Net Worth)
- Clean, professional layout



