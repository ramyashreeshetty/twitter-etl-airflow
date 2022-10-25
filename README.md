# Twitter Data Pipeline 

This pipeline is built using Airflow and Python.

## How it works
- Data is extracted using Twitter API.
- Then it is transformed using python and its libraries.
- Create an EC2 instance (Ubuntu) and output S3 bucket. (Also, setup the airflow in EC2)
- Deploy the code onto EC2 and airflow.
- Airflow schedules and runs the code which saves the result onto the S3 bucket.


![image](https://user-images.githubusercontent.com/43513353/197874231-7492ef71-1ee9-46ff-b87e-fdaf73786f56.png)

