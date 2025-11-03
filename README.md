# NHS Lab ETL Pipeline

This project simulates a basic ETL (Extract, Transform, Load) pipeline using NHS-style lab test data. It demonstrates how to clean, transform, and visualize healthcare data using Python and Power BI.

🔧 Tools Used
- Python (Pandas)
- Google Colab
- Power BI Desktop
- CSV files

📁 Files
- `lab_results.csv`: Raw mock lab data
- `etl_pipeline.ipynb`: Python notebook for cleaning and transforming data
- `abnormal_summary.csv`: Output summary of abnormal results by lab location

🚀 How to Run This Project

1. Open `etl_pipeline.ipynb` in [Google Colab](https://colab.research.google.com) or Jupyter Notebook.
2. Upload `lab_results.csv` when prompted.
3. Run each cell to:
   - Clean missing values
   - Flag abnormal results
   - Group by lab location
   - Export the summary to `abnormal_summary.csv`
4. Open `abnormal_summary.csv` in Power BI Desktop or Excel to visualize the results.


📊 Visualizations
The final output was visualized in Power BI as a bar chart showing abnormal result counts per lab.

🎯 Skills Demonstrated
- Data cleaning (handling missing values, formatting dates)
- Data transformation (flagging abnormal results, grouping)
- ETL logic simulation
- Healthcare domain relevance

🚀 Next Steps
- Add date-based trends and test type filters
- Explore storing data in SQL or cloud platforms
- Expand to HL7/FHIR integration simulation

---

This project is part of my transition into data engineering, building on 10+ years of healthcare IT experience.
This project is part of my freelance data engineering portfolio, focused on healthcare data workflows and NHS-relevant analytics. Feel free to fork, adapt, or connect if you're working on similar problems.

