# DB2019S_FINAL  
Database System 2019 Spring Final Project  
  
## Environment  
Python 3.6  
psycopg2, numpy, pandas  
  
## Datasets Source
Hospital Payment: https://data.medicare.gov/api/views/c7us-v4mf/rows.csv?accessType=DOWNLOAD
Deaths and Complications: https://data.medicare.gov/api/views/ynj2-r877/rows.csv?accessType=DOWNLOAD

  
## Members:  
Yihao Huang  
Ian Diaz  
Hantian (Simon) Jiang  
Zhengyi Shi  

1. Get compFile and paymentFile from datasets.txt. Place them inside of the DATA folder. 
		Since the paths are dependent on the data being there, moving the csv will break functionality
2. Run hospital.sql to set up the database 
3. Run load_data.py to populate the database. 
   Make sure to change "compfile" and "paymentfile" in load_data to reflect location and name of the csv's
   (placing the two csv's in the same folder as load_data.py with the default names should work)
4. Run python3 application.py