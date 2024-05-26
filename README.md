# DataMaster Toolkit

The DataMaster Toolkit is a collection of Python scripts designed to help with various data tasks such as data extraction, cleaning, analysis, export, and transformation using PySpark.

## Files

1. **data_extraction.py**: Script to extract data from a CSV file.
2. **data_cleaning.py**: Script to perform basic data cleaning tasks.
3. **data_analysis.py**: Script to perform basic data analysis tasks.
4. **data_export.py**: Script to export data to an Excel file.
5. **data_transformation.py**: Script to perform data transformations using PySpark.
6. **databricks_example.py**: Script to connect and work with a Databricks cluster.
7. **local_pyspark_example.py**: Script to work locally with PySpark.

## Requirements

- Python 3.x
- Pandas library (`pip install pandas`)
- Matplotlib library (`pip install matplotlib`)
- PySpark library (`pip install pyspark`)
- Databricks Connect library (`pip install -U databricks-connect`)

## Usage

### 1. Data Extraction from CSV

**Script:** `data_extraction.py`

**Description:** This script extracts data from a CSV file and loads it into a Pandas DataFrame.

**Usage:**
```bash
python data_extraction.py
