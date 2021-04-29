# Data-Pipeline-Project with Airflow
 The project contain a piplene  to build a data schema for music app data analysis.
 
 ### Architecture description: 
 the data pipline was constructed using a number of tools: 
 
   1.S3 Bucket - The app data stored in JSON files and was loaded to S3 bucket: s3://udacity-dend/log_data/.
   
   2.Docker Image - The docker container used for createing an environment for running Airflow dag.
  
   3.Airflow Dag - The airflow dag is responsible for the etl procedure. The dag runs daily, extracts data from s3, transforms it into a data schema and loads it into redshift.
   
   4.Redshift - The final data is stored in redshift and can be queried using Amazon Athena.


  
  
![תמונה](https://user-images.githubusercontent.com/57598804/116536602-d0e02c80-a8ed-11eb-85e6-d26d1cb87c45.JPG)

  
 
 
 
  
  

