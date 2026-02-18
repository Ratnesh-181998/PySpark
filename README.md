# PySpark

## PySpark – Complete Data Engineering & Big Data Interview Guide
- A structured reference covering PySpark fundamentals, DataFrame operations, schema handling, joins, complex data types, and UDFs for scalable data processing.

## Pyspark-1

- What this document covers:
  
### • PySpark Fundamentals
- Apache Spark & PySpark overview
- Distributed computing & in-memory processing
- Use cases: Batch processing, Streaming, ML, ETL
- Spark Cluster (Master & Worker nodes)
- SparkSession as the entry point

###  • PySpark DataFrames
- Distributed alternative to Pandas
- Creating DataFrames using read.csv(), read.json(), read.parquet()
- header=True & inferSchema=True usage
- df.show(), df.printSchema(), df.count()
  
### • DataFrame Core Operations
- select(), filter(), where()
- groupBy() & agg()
- Sorting using sort() & orderBy()
- SQL-equivalent mapping (SELECT, WHERE, GROUP BY, AGGREGATE)
  
###  • Handling Missing Data
- .na.drop() (drop null rows)
- .na.fill() (replace nulls with default values)
- Filtering using isNotNull()
  
###  • Column & Row Operations
- withColumn() (create new columns)
- withColumnRenamed()
- drop()
- Filtering rows with conditions
- Grouping & aggregations (sum, avg, count)
  
###  • Schema & Data Types
- StructType & StructField
- IntegerType, StringType, DoubleType
- Manual schema definition vs schema inference
- Working with CSV & JSON using defined schemas
  
### • Joins & Union
- Inner, Left, Right, Full Outer Joins
- join() syntax with condition
- union() for stacking DataFrames
- Schema alignment requirements
  
###  • Complex Data Types
- Arrays
- Maps (key-value pairs)
- Structs (nested structured fields)
  
### • UDFs (User Defined Functions)
- Defining and registering PySpark UDFs
- Applying UDFs with withColumn()
- pandas UDFs for large datasets
- Performance comparison: PySpark UDF vs pandas UDF
- Vectorized processing with @pandas_udf
- A complete PySpark reference for Data Engineers, Big Data Developers, and Spark interview preparation.

