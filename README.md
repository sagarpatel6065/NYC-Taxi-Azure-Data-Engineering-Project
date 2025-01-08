# NYC Taxi Data Engineering Project  

## Overview  
This project demonstrates an end-to-end data engineering solution for processing NYC Taxi data using modern tools like Azure Data Factory, Databricks, and Delta Lake.  

## Architecture  
![Medallion Architecture](./assets/medallion_architecture.png)  

## Tools and Technologies  
- **Azure Data Factory**: For dynamic pipelines.  
- **Azure Data Lake Storage Gen2**: For data storage.  
- **Databricks (PySpark)**: For data transformation.  
- **Delta Lake**: For time travel and versioning.  
- **Power BI**: For visualizing results.  

## Steps to Reproduce  
1. Set up Azure Free Account.  
2. Configure Azure Data Lake and Data Factory.  
3. Import the provided ADF pipeline template and scripts.  
4. Set up Databricks and run the notebooks for transformations.  
5. Visualize the Gold layer in Power BI.  

## Repository Contents  
- `assets/`: Architecture diagrams and visuals.  
- `data/`: Sample Parquet and CSV files.  
- `notebooks/`: Databricks notebooks for data transformations.  
- `pipeline/`: Exported JSON/ARM templates for ADF pipelines.  
- `scripts/`: Python scripts for automation.  

## Sample Dashboard  
![Power BI Dashboard](./assets/powerbi_dashboard.png)  

## License  
This project is licensed under the MIT License.
