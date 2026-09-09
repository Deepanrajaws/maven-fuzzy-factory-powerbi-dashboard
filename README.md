
# Maven Fuzzy Factory — Executive Business Intelligence Dashboard

[🚀 View Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmRkNTlhYzctODU3ZS00YzJlLThjODUtMzc3NjkxZWVlMjRhIiwidCI6IjUwOTE2YjViLWM4MmUtNGJlNC05YmIyLWFkN2YzYmI3ZTAzYyJ9)

## Project Overview
An executive 3-page Power BI dashboard designed to analyze financial performance, product economics, conversion funnel drop-offs, and channel traffic for Maven Fuzzy Factory (2012–2015).

## Key Features & Visuals
* **Page 1: Executive Overview & Channel Performance** — High-level revenue trends and marketing channel analysis.
* **Page 2: Product Economics** — Granular unit economics breakdown including Gross Margin %, Gross Profit, COGS, and AOV.
* **Page 3: Conversion Funnel & Pageview Analytics** — Step-by-step website funnel drop-off and bounce rate tracking.

## Core Financial DAX Measures
```dax
Total COGS = SUM(order_items[cogs_usd])
Gross Profit = [Total Revenue] - [Total COGS]
Gross Margin % = DIVIDE([Gross Profit], [Total Revenue], 0)
