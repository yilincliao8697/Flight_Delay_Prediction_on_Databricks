Flight Delay Prediction on Databricks (Azure Cloud)

This project involves building a machine learning solution on the Databricks platform to predict U.S. domestic flight delays using large-scale flight and weather data from 2015–2021. The workflow includes accessing a shared Databricks workspace, cloning a starter notebook, connecting to a Spark cluster, and configuring Azure Blob Storage with secure credentials.

The objective is to frame a predictive modeling task—such as forecasting whether a flight will be delayed by 15+ minutes at least two hours before departure—and select appropriate evaluation metrics (e.g., F1-beta, specificity, R²) based on the problem formulation (classification or regression).

Key datasets include:

Flight data from the U.S. Department of Transportation, with over 31 million records.

Weather data from NOAA, covering over 630 million records.

Airport metadata and airport codes for enrichment and joining.

ATPW dataset, which combines flight performance and local weather data.

Initial analysis is performed on smaller subsets (e.g., 3 or 6 months of data) before scaling to the full multi-year dataset. The final product is a predictive model that supports operational decisions for stakeholders such as airlines, airports, or regulatory bodies.
