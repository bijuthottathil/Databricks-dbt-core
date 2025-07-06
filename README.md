# Load CSV data from dbt seed to Databricks Schema
![image](https://github.com/user-attachments/assets/79283537-a7f8-469e-8765-bdc63696488a)

1. python -m venv venv_dbt  

2. venv_dbt\Scripts\activate
3. pip install dbt-databricks
4. dbt init dbt_project_databricks
  cd dbt_project_databricks

5. dbt init
![image](https://github.com/user-attachments/assets/de0373f8-0f94-4e95-8560-b1301ad5610a)

6. dbt debug
     
8. ![image](https://github.com/user-attachments/assets/a5355a8b-e1aa-42c3-b3ee-91982b0100dc)
9. Basic example to load data from customer csv by putting under seeds and insert to Schema in Databricks

9.![image](https://github.com/user-attachments/assets/11939325-bf9f-447f-8ce7-ba55ad1bef15)  

 

10. ![image](https://github.com/user-attachments/assets/f5d730d5-170b-43c3-93fe-6e7bd24f157e)  

11. ![image](https://github.com/user-attachments/assets/56c44833-ef81-4007-a443-21b635a2b6cf)
12.  Next I am running DBT Run to execute below model I set it under models folder
13.  ![image](https://github.com/user-attachments/assets/bccea954-fec7-4cf8-b6c3-6c261e497357)
14.  Execute dbt run command   
15.  ![image](https://github.com/user-attachments/assets/0b8519a5-7faf-4235-8543-06da8e66b372)
16.  Check the result in Databricks
17.  ![image](https://github.com/user-attachments/assets/e2f78283-89ad-4a28-8742-e2b6efd983c3)
18.  You can see delta table created for Customers table in Databricks Catalog/Schema ..

19.  ![image](https://github.com/user-attachments/assets/b6ceffb3-c13f-4daa-9817-126cee81f621)






