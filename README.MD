AdventureWorks Sales Analytics Dashboard | Power BI

Designed and developed an advanced Power BI dashboard using the AdventureWorks database to analyze sales performance across products, territories, salespersons, and order lifecycle stages.

Connected to the AdventureWorks SQL Server database using DirectQuery to enable near real-time reporting.

Integrated and modeled data from multiple fact and dimension tables, including sales orders, products, territories, shipping methods, and salespersons.

Implemented data cleaning, transformation, and enrichment using Power Query (M Language):

Created a unified Product dimension by merging Product, Subcategory, and Category tables.

Added calculated columns such as Order Status using database functions.

Built a dedicated Date table to support time-based analysis.

Renamed tables and columns and removed unused attributes for optimized modeling.

Designed a Star Schema data model to improve performance, scalability, and analytical clarity.

Created a Product Hierarchy (Category → Subcategory → Product) to support drill-down analysis.

Developed advanced DAX measures for key business metrics, including:

Number of Orders

Order Quantity

Subtotal, Tax, Freight, and Total Due

Implemented role-playing date dimensions (Order Date, Ship Date, Due Date) using inactive relationships and USERELATIONSHIP to enable flexible date-based analysis.

Built a centralized DAX measures table to organize all business calculations.

Designed interactive visuals including drill-down, drill-through pages, and custom tooltip pages.

Delivered actionable insights on order volume, revenue distribution, shipping methods, online vs. offline sales, top-performing salespersons, and territorial performance.
