📦 Demand Forecast & Inventory Validation Pipeline

This project automates the processing of large retail datasets (10M+ rows) to support demand forecasting and inventory validation. It ingests daily IT export files, applies business rules (company and department filters), calculates key stock and sales metrics, aggregates results by reporting date, and produces clean validation reports.

Designed for real-world FMCG retail environments, the pipeline uses memory-efficient chunk processing to handle large data volumes without performance issues. A typical report covering ~10 million rows is generated in approximately 5–15 minutes, depending on hardware and file size.

🔑 Key Features

-Processes multiple daily exports automatically

-Extracts reporting dates from file names

-Filters by business units and departments

-Computes inventory and sales KPIs

-Aggregates data for validation reporting

-Handles very large datasets efficiently

-Produces ready-to-use CSV reports for analysis, purchase planning, and inventory replenishment
