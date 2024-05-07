Predictive Analysis on Motor Vehicle Collision in NYC

Step 1: Collected Dataset from open data 'data.gov' website. 

step 2: Done Data ingestion using gsutil. 

step 3: Stored data in Google Cloud Platform.

step 4: Accessed data from GCP and further cleaning and preprocessing it using pyspark.

How to run this project?

1. Prerequisite: Ensured that python 3 is installed on your local machine, which is required for running some components of Google Cloud SDK.
2.	Install cloud SDK: Install Google Cloud SDK on your local machine to interact Google Cloud Platform (GCP) Services.
3.	Authentication: Used ‘gcloud auth login’ to authenticate with Google Cloud SDK, allowing you to access GCP resources.
4.	Initialization: Run ‘gcloud init’ to initialize the Google Cloud SDK on your local machine, configuring it with your preferences and credentials.

5. You must have access to get data from GCP.
6. once you are done, you are ready to run the notebook.

7. Here to get data from GCP to your system, you must have "gcs-connector-hadoop3-latest.jar" file and "bigdata-project-603-cbaafc8fbd38.json" file in your system
8. Your jar file must be in jars directory of your Apache Spark installation.

9. First there is file "1. Data collection to Storage" -- in this step i gave details about how to upload data using gsutil commands to Google cloud Storage.
10. And then once uploaded to cloud storage, you are ready to use that data.
11. And the next step is, there is a file called "Data reading from gcp and data cleaning.ipynb" you can download and run this. Through this file we can get data from cloud storage and done some data cleaning.
12. and the next file is "3. Feature Engineering and Data Analysis.ipynb" -- Here feature engineering and Data analysis had done 
13. the next file is "4. Feature Engineering and Data Balancing.ipynb" -- Here Data balancing has done
14. The next file is "5. Data Modelling using MLlib.iynb" -- making predictions in this file
