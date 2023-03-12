
## YELP data set Data Engineering and Machine Learning Practice



In This project:
1. Data Extraction: Using **Kaggle API** to download the Yelp Dataset to DataProc Master node. (>8GB after unzip)
2. Data Transformation: Upload the unzipped data to **Hadoop File System**; Used **pyspark** to clean the transform the dataset, then load into **HIVE** tables in Hadoop. 
3. Performed Exploratory Data Analysis with Pyspark and Pandas, found the best 10 popular restaurants in Philadelphia.
4. Created DataLayer, by de-normalizing the 5 tables; saved the data as Avro format in **CloudStorage** and loaded into **BigQuery**. (Connected Dataproc cluster to CloudStorage directly, used CloudStorage as DataLake)
5. .TODO ..perform ML using BigQuery ML. 





------
Resources:

How to connect DataProc to BigQuery
https://cloud.google.com/dataproc/docs/tutorials/bigquery-connector-spark-example#pyspark