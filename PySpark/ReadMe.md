# PySpark Practice for Data Analysts

This folder contains practical PySpark exercises designed to help learners build skills needed for Data Analyst and Data Engineering roles. The examples focus on real analytics tasks using Spark DataFrames, transformations, UDFs, and lazy evaluation.

## File Format Notice
The PySpark practice notebook is provided in HTML format. This makes it easy to open directly in any web browser without needing Databricks or a local PySpark setup. You can view the code, explanations, and outputs immediately.

## What’s Included

### Spark Basics
- Creating a SparkSession
- Importing functions and window operations
- Building DataFrames from sample data

### DataFrame Operations
- Selecting and transforming columns
- Filtering and sorting
- Adding derived columns
- Using built‑in functions from pyspark.sql.functions

### Lazy Evaluation Demo
Examples showing how Spark delays execution until an action is called.  
The notebook includes code such as:

> “df2 = df.withColumn("name_upper", my_udf("name"))”

to demonstrate how transformations are defined but not executed immediately.

### UDF Usage
- Creating Python functions
- Registering them as UDFs
- Applying UDFs to DataFrame columns
- Understanding when Spark triggers execution

### Window Functions
Examples using pyspark.sql.window to perform analytics tasks such as ranking and aggregations over partitions.

## Purpose
These PySpark exercises help Data Analyst learners understand how Spark processes data, how transformations work, and how to apply PySpark in real analytics workflows.

## How to Use
Open the HTML file in your browser to view the examples. You can also copy the code into Databricks or any PySpark environment to run and modify the exercises.

## License
This content is provided for learning and practice. You may reuse the examples with attribution.
