
## Repository Structure

```text
superstore-fabric-analytics/
├── README.md                              # Main project documentation
├── architecture/
│   └── architecture_diagram.png           # Data flow diagram
├── notebooks/
│   ├── Day1_Parquet_Delta.ipynb
│   ├── Bronze_to_Silver_Transform.ipynb
│   ├── Silver_to_Gold_Transform.ipynb
│   ├── Incremental_Load.ipynb
│   ├── Data_Quality_Checks.ipynb
│   ├── Advanced_PySpark.ipynb
│   └── Audit_Log.ipynb
├── screenshots/
│   ├── page1_executive_overview.png
│   ├── page2_product_analysis.png
│   ├── page3_customer_analysis.png
│   ├── pipeline_canvas.png
│   └── audit_log_results.png
└── docs/
    ├── data_dictionary.md                 # Column definitions for all Gold tables
    └── audit_log.md                       # Copy of the Day 19 audit results
```
# superstore-fabric-analytics
End-to-end Microsoft Fabric data engineering and Power BI analytics project using PySpark, Delta Lake, Medallion Architecture, and CI/CD with GitHub.
