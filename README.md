Global-sales-of-chocolates-during-a-particular-period-in-the-World:
This dashboard is designed to provide actionable insights for decision-making, helping businesses identify high-performing regions, products, and sales contributors.

Problem Statement
Sales data for a chocolate distribution business — covering products, sales representatives, regions, shipment dates, and shipment costs/quantities — was scattered across raw transactional records with no easy way for stakeholders to track performance. The objective of this project was to consolidate this data into a single interactive Power BI dashboard that lets management quickly answer:

- Which products and salespeople are driving the most sales (by box volume/amount)?
- How are sales trending over time (year, quarter, month, day)?
- How is sales performance distributed across regions?
- What is the cost efficiency per box shipped relative to total sales?

Tools & Technologies Used
- Power BI Desktop – primary tool used to build the data model, DAX measures, and report visuals.
- Power Query (M) – used within Power BI to import, clean, and shape the source data into a structured model (products, sales reps, regions, and shipment tables).
- DAX (Data Analysis Expressions) – used to create calculated measures, such as `Amount x Boxes` (total sales value) and `Cost per Box`, that power the visuals and KPI card.
- Power BI Report Canvas – used to design a single-page report combining slicers, a treemap, a donut chart, a ribbon chart, and a KPI visual on a shared theme (CY24SU10).

Dashboard Structure & Visuals
The report is built as a single, focused page titled "Global Sales of Chocolates During a Period", containing the following visuals:

Analysis & Insights

1. Product-Level Filtering Drives Drill-Down Analysis
The advanced product slicer, sorted by sales amount, immediately surfaces the best- and worst-performing chocolate products, allowing stakeholders to isolate any single product's contribution across all other visuals on the page.

2. Salesperson Performance is Highly Visual via Treemap
The treemap by salesperson uses tile size to represent sales volume, making it easy to spot top performers at a glance — useful for identifying who to recognize for strong performance or who may need support.

3. Time-Based Trends are Captured at Multiple Granularities
By breaking shipment dates into year, quarter, month, and day, the donut chart enables both a high-level (yearly) view and the ability to drill into seasonal or monthly sales patterns — helpful for spotting peak chocolate sales periods (e.g., holiday season spikes).

4. Regional Competitiveness via Ribbon Chart
The ribbon chart for regions doesn't just show totals — it visualizes how each region's sales ranking shifts over the selected dimension, which is valuable for spotting regions that are gaining or losing ground relative to others.

5. Cost Efficiency Tracked Alongside Volume
The KPI card pairs Cost per Box with Amount x Boxes, giving a quick efficiency check: are sales volumes growing while cost per unit stays controlled, or is cost creeping up as volume increases? This is a key profitability signal for management.

6. Interactivity as a Core Design Choice
With two slicers (Product and Ship Date) feeding into all four core visuals, the dashboard is built for exploratory, self-service analysis rather than a static report — users can isolate any product or date range and instantly see how sales by salesperson, time, region, and cost efficiency respond.

Conclusion
This dashboard turns raw chocolate shipment/sales data into a compact, interactive single-page report that supports sales performance reviews, time-trend analysis, regional comparisons, and cost efficiency tracking — all from one screen, filterable by product and date.

Key Highlights:
- Interactive date slicer to analyze trends over time
- Region-wise and product-wise sales breakdown
- Insightful year-over-year comparison (2023 vs 2024)
- Dynamic treemap visual showcasing top-performing salespeople
- Clear identification of top product categories driving revenue
