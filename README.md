📊 Sales Data Analysis Dashboard
A comprehensive interactive dashboard built to provide key insights into sales performance, product categories, and regional trends.
🌟 Overview
This project provides a clear, interactive visualization of sales data, enabling stakeholders to track performance, identify top-selling products, and understand geographical contributions to total sales. The project leverages robust data cleaning, a defined data model, and a custom-designed user interface.
🛠️ Technology Stack
| Component | Tool Used | Purpose |
|---|---|---|
| Data Preparation & ETL | Power Query (within Power BI) | Cleaning, transforming, and loading raw sales data. |
| Data Modeling & Analysis | Power BI Desktop | Creating relationships, defining measures (DAX), and building the interactive report. |
| Visual Design & UX | Figma | Designing a custom, cohesive, and user-friendly dashboard background and layout. |
🚀 Key Features
 * Interactive Filters: Easily filter data by Territory, Product Category, and Time Period (e.g., Year/Quarter).
 * Key Performance Indicators (KPIs): Instant visibility of total Line Total, Order Quantity, and Freight costs.
 * Geographical Breakdown: Visual mapping and tables to understand sales distribution across different regions/territories.
 * Product Insights: Analysis of performance by Product Category and Product SubCategory.
📁 Project Structure
 * Sales_Original.xlsx - Sales.csv: The raw source data used for the analysis.
 * Data analysis Dashboard.pbix: The main Power BI project file containing the report, data model, and DAX calculations.
 * Data analysis Dashboard.png / BackGround_DataAnalysis dashboard.png: Final dashboard preview and custom background image.
 * Modeling.png: Screenshot of the Data Model showing table relationships.
⚙️ How to View and Interact
Prerequisites
To open and interact with the .pbix file, you must have Power BI Desktop installed on your system.
Steps
 * Download the entire repository.
 * Open the Data analysis Dashboard.pbix file using Power BI Desktop.
 * The report will automatically refresh (if the data source path is maintained or updated).
 * Use the slicers and visuals to cross-filter the data and explore different segments of the sales figures.
✨ Design & Customization (Figma)
The design of the dashboard, including the layout, color scheme, and specific background elements, was prototyped and created in Figma to ensure a professional and unique aesthetic.
 * The custom background image (BackGround_DataAnalysis dashboard.png) was exported from the Figma design and imported into Power BI to serve as the visual foundation for the report.
🧼 Data Preparation Details (Power Query)
The raw data was transformed using Power Query (M Language) to ensure data quality and structure. Key steps included:
 * Data Type Correction: Ensuring all numerical fields (e.g., LineTotal, OrderQty) and date fields (OrderDate, ShipDate) are correctly formatted.
 * Missing Value Handling: Checking and cleaning any blank or null values.
 * Date Dimension: Extracting Year, Quarter, and Month columns from the OrderDate for time intelligence analysis.
🔗 Data Modeling (Power BI)
The project uses a Star Schema to optimize performance and calculation simplicity.
 * A central Fact Table (Sales data) is connected to smaller Dimension Tables (e.g., Product Category, Territory).
 * Refer to Modeling.png for a visual representation of the established data model.
📧 Contact
For any questions or suggestions regarding this dashboard, please contact:
Ahmed Ayman Mohammed Fayed 
5000ahmedayman5000@gmail.com
