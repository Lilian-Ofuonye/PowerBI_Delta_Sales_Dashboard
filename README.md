## Sales Performance Dashboard (Power BI)
#### Overview

This project presents a revenue-led sales performance dashboard built in Power BI, designed for fast executive scanning with the option to drill into product-level detail.
The report focuses on clarity and business relevance.

#### Business Questions Answered

* How much revenue, profit, and volume has the business generated?
* Which categories and sub-categories drive the most revenue?
* How does revenue performance vary by state?
* Which products are high-revenue but low-margin?
* How does revenue trend over time?

### Dashboard Structure
#### Overview Page

This shows an executive summary focused on revenue performance:
* Total Revenue, Profit, Quantity Sold, and Customers
* Revenue share by category
* Top states by revenue contribution (bar + map)
* Revenue by payment method
* Quarterly revenue trend

Profit and margin are intentionally exposed via tooltips to avoid clutter while preserving analytical depth.

#### Product Detail Page
A focused drill-down view for sub-category performance:
* Revenue, Profit, Profit Margin, and Quantity in a single matrix
* Conditional formatting to highlight margin efficiency
* Supporting revenue bar chart for visual comparison

This page is designed to identify:
* High-revenue / low-margin products
* Strong, efficient performers
* Products that may require pricing or cost review

### Key Design Decisions
* Revenue-first narrative to establish scale and demand
* Profit and margin in tooltips to reduce visual noise
* Minimal colour palette for readability and consistency
* Conditional formatting used sparingly to guide attention, not distract

### Tools Used
* Power BI Desktop
* DAX (measures for revenue, profit, margin)
* Power Query (data preparation)

### Repository Content
* README.md
* Screenshots of dashboard and product detail page
* Dataset

## Author
Built as a portfolio project to demonstrate Power BI modelling, visual design, and analytical judgement.
