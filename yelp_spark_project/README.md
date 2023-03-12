
# YELP data set Data Engineering and Machine Learning Practice (GCP)

#### keyworks: Hadoop, HIVE, Spark, GCP, BigQuery, CloudStorage, DataProc, Python, SQL, Pandas

### Key Practices In This project:
1. Data Extraction: Using **Kaggle API** to download the Yelp Dataset to DataProc Master node. (>8GB after unzip)
2. Data Transformation: Upload the unzipped data to **Hadoop File System**; Used **pyspark** to clean the transform the dataset, then load into **HIVE** tables in Hadoop. 
3. Performed Exploratory Data Analysis with Pyspark and Pandas, found the best 10 popular restaurants in Philadelphia.
4. Created DataLayer, by de-normalizing the 5 tables ( processed >320 million records); saved the data as Avro format in **CloudStorage** and loaded into **BigQuery**. (Connected Dataproc cluster to CloudStorage directly, used CloudStorage as DataLake)
5. .TODO ..perform ML using BigQuery ML. 







----
## Screenshots:

### Hive tables:

![img.png](images%2Fimg.png)

### Parquets in CloudStorage
![2023-03-12_19-18-25.png](images%2F2023-03-12_19-18-25.png)
### Loading to BigQuery

![2023-03-12_19-10-48.png](images%2F2023-03-12_19-10-48.png)

![2023-03-12_19-17-27.png](images%2F2023-03-12_19-17-27.png)

### ML 



------
Resources:

How to connect DataProc to BigQuery
https://cloud.google.com/dataproc/docs/tutorials/bigquery-connector-spark-example#pyspark

