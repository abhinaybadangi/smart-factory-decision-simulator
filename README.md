# Smart Factory Decision Simulator

Interactive Power BI dashboard that simulates how cost, demand, and defect rates impact production profitability in real time.

## Overview

Smart Factory Decision Simulator is a scenario-based Power BI project designed to help decision-makers understand how operational changes affect factory performance. Users can adjust key business drivers using interactive controls and instantly see the impact on KPIs, production flow, cost structure, and profit.

This project focuses on turning a dashboard into a decision tool by combining:

- what-if parameters
- advanced DAX measures
- dynamic KPI recalculation
- Sankey-based production-to-profit flow analysis
- automated insight generation
- modern dark-themed UI

## Business Problem

Manufacturing teams often struggle to understand how small operational changes influence profitability. Rising costs, fluctuating demand, and defect rates can quickly affect output and margins.

This dashboard solves that problem by allowing users to simulate those changes in real time and visually trace their impact from production to profit.

## Objectives

- Simulate operational scenarios using parameter-driven inputs
- Show how cost, demand, and defects influence performance
- Visualize the production-to-profit journey clearly
- Provide a premium, interactive Power BI experience
- Demonstrate advanced analytical storytelling for portfolio and recruiter review

## Features

- **Scenario Controls**
  - Cost Change %
  - Demand Change %
  - Defect Change %

- **Dynamic KPI Cards**
  - Sales
  - Quantity
  - Cost
  - Discount / Defect-related metric

- **Interactive Sankey Flow**
  - Raw Material -> Production -> Good Units / Defective Units -> Revenue / Loss -> Profit

- **Cost Breakdown Panel**
  - Simulated cost composition across major cost types

- **Profit Trend Panel**
  - Quick trend view for scenario comparison

- **Insight Engine**
  - Dynamic narrative summarizing the current simulated business state

## Data Model

This project uses a star-schema-inspired model with:

### Fact Table
- `fact_factory_daily`

### Dimension Tables
- `dim_date`
- `dim_plant`
- `dim_product`
- `dim_scenario`
- `Cost Type` (disconnected helper table)
- `Sankey` (helper table for flow visualization)

## Key Measures

Examples of core measures used:

- `Adjusted Revenue`
- `Adjusted Units Sold`
- `Adjusted Total Cost`
- `Adjusted Defective Units`
- `Adjusted Profit`
- `Adjusted Defect Rate %`
- `Insight Text`
- `Flow Value`
- `Adjusted Cost Value`

## Tools & Technologies

- **Power BI**
- **DAX**
- **CSV / Excel data modeling**
- **What-if Parameters**
- **Sankey Visual**
- **Custom UI design in Power BI**

## Dashboard Preview

Add screenshots here after exporting from Power BI.

### Recommended Screenshots
1. Full dashboard view
2. Sankey simulation focus
3. Parameter controls + insight panel

## How It Works

1. Users adjust scenario sliders
2. Parameters trigger adjusted DAX measures
3. KPI cards and supporting visuals recalculate instantly
4. Sankey flow updates to reflect operational movement
5. Insight panel generates a readable business summary

## Why This Project Stands Out

Most Power BI portfolio projects are descriptive dashboards.

This project is different because it acts as a **decision simulator** rather than a static report. It demonstrates:

- analytical thinking
- scenario modeling
- business storytelling
- UI/UX design discipline
- recruiter-friendly project positioning

## Repository Structure

```text
smart-factory-decision-simulator/
│
├── data/
│   ├── fact_factory_daily.csv
│   ├── dim_date.csv
│   ├── dim_plant.csv
│   ├── dim_product.csv
│   ├── dim_scenario.csv
│   └── data_dictionary.csv
│
├── images/
│   ├── dashboard-overview.png
│   ├── sankey-focus.png
│   └── controls-insight.png
│
├── pbix/
│   └── Smart_Factory_Decision_Simulator.pbix
│
└── README.md
```

## Resume-Friendly Summary

Built an interactive Power BI decision simulator using what-if parameters and advanced DAX to model the impact of cost, demand, and defects on manufacturing profitability.

## Portfolio Summary

A scenario-driven Power BI project designed to simulate operational outcomes and help stakeholders understand how production, loss, revenue, and profit respond to changing business conditions.

## Future Enhancements

- Tooltip pages for deeper drill insights
- Scenario bookmarks for guided storytelling
- Plant-level benchmarking
- Forecast-driven simulation layer
- Export-ready executive summary page

## Author

**Abhinay Badangi**  
Data Analyst | Power BI | SQL | Python  
Portfolio: https://abhinaybadangi.github.io/portfolio/
