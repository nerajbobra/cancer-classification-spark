# cancer-classification-spark
Cancer classification using random forest with PySpark ML

This project utilizes PySpark's ML library to classify benign or malignant tumors (cancer) based on a random forest model. DataFrames and pipelines are used to efficiently and concisely implement the entire workflow. 

Note that this project uses the databricks package to load CSV files directly to a DataFrame. Use the following command to load PySpark in a notebook:
PYSPARK_DRIVER_PYTHON=ipython PYSPARK_DRIVER_PYTHON_OPTS="notebook" $SPARK_HOME/bin/pyspark --packages com.databricks:spark-csv_2.10:1.3.0
