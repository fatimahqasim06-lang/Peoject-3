E-Commerce Data Analytics Pipeline

Project Overview

This notebook implements a comprehensive business intelligence pipeline that transforms raw e-commerce transaction data into actionable insights through structured SQL queries. The script loads an Excel dataset into an in-memory SQLite database and executes fifteen analytical queries covering key business dimensions including basic statistics, product performance, order status distribution, payment method analysis, customer segmentation, marketing channel effectiveness, coupon code performance, high-value order identification, cancelled and returned order analysis, monthly sales trends, product demand ranking, cart size analysis, cross-tabulation of order status by payment method, product failure rate calculation, and an executive summary dashboard. This approach enables efficient data processing and reproducible analytics without persistent storage overhead.

Methodology

Upon loading the data, the script establishes an in-memory SQLite database and loads the DataFrame as a table. Each of the fifteen queries addresses a distinct business question, leveraging SQL aggregations, conditional logic with CASE statements, temporal extraction using SUBSTR, and UNION ALL operations to consolidate metrics. Results are returned as pandas DataFrames and printed to the console in formatted tables, providing a complete operational picture from order fulfillment rates and revenue streams to customer lifetime value and marketing ROI.

Output and Applications

The console output delivers fifteen structured result sets that collectively form an executive-level business review. Key deliverables include identification of products with elevated failure rates requiring quality intervention, evaluation of marketing channel performance to guide budget allocation, assessment of promotional code effectiveness, quantification of revenue loss from failed orders, and a consolidated KPI dashboard for ongoing performance monitoring. This pipeline serves as the final stage in a complete data analytics workflow, following data cleaning and exploratory analysis to deliver actionable business intelligence
