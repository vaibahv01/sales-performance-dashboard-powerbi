# Sales Performance Dashboard (Power BI)

An interactive dashboard analysing sales revenue, orders, and cancellations
across 5 countries.

## Business Questions
- Where does revenue come from (category, product, country)?
- How does YTD revenue compare with the same period last year?
- What is the cancellation rate and how can it be reduced?

## Dashboard Preview
![Dashboard Overview](images/dashboard-overview.png)

## Key Insights
- Electronics generates the largest share of revenue
- Cancellation rate is 8.33%


## Features
- KPI cards: revenue, orders, AOV, cancellation rate
- YTD vs. prior year comparison using DAX time intelligence
- Monthly trend, category and product breakdowns
- Slicers for year and country

## DAX Highlights
```DAX
Revenue YTD = TOTALYTD([Total Revenue], 'Date'[Date])
Revenue PY = CALCULATE([Total Revenue], SAMEPERIODLASTYEAR('Date'[Date]))
```

## Tools
Power BI Desktop, DAX, Excel

## How to Open
1. Download `SalesDashboard.pbix`
2. Open with Power BI Desktop (free from Microsoft)


