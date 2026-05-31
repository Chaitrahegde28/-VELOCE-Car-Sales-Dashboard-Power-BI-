# 🚗**VELOCE-Car-Sales-Dashboard-Power-BI**

A dark-themed interactive sales dashboard built in Power BI, inspired by the Acura Sales Dashboard concept. This project uses a real-world used car dataset with over 558,000 rows to visualize sales performance across four major US car brands — Ford, Chevrolet, Nissan, and Toyota.

#**📊 Features**

4 Brand Pages — Ford, Chevrolet, Nissan, and Toyota, each as a separate Power BI page with page navigation buttons
KPI Cards — Total Sales (sum of selling price), Total Orders (count of VIN), Total Sellers (distinct count of seller)
Hero Car Section — Transparent PNG car image with model name, subtitle, and starting price overlay
Sales By Year — Horizontal bar chart showing revenue per year extracted from sale date
Sales By Paint Color — Column chart with top 6 colors and hexagon color swatches using Chiclet Slicer
Sales by Deal Size — Donut chart with Small, Medium, and Large deal categories
Sales by State — Bubble map showing sales volume across US states
Dark Theme — Full dark canvas with brand-specific accent colors per page

#**🛠️ How It Was Built**

*Tools Used*

Power BI Desktop — Main dashboard tool
Power Query — Data cleaning and transformation
DAX — Measures for KPIs
remove.bg — Background removal for car images

#**Deal Size Logic**

if sellingprice < 10000  → Small
if sellingprice < 25000  → Medium
else                     → Large

#**💡 Key Learnings**

How to build a multi-page dark themed dashboard in Power BI
Using page navigation buttons to simulate tab switching
Creating conditional columns in Power Query for deal size segmentation
Extracting year from a complex date string using M formula
Layering images, shapes, and text boxes to create a hero section
Grouping visuals so they move together on the canvas
Using Chiclet Slicer for interactive hexagon color filters

#**⭐ If you found this useful, give it a star on GitHub!!!!!!**
