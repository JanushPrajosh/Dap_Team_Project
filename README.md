# DAP TEAM PROJECT
## A case study on New York Restaurants
[![N|Solid](https://fiverr-res.cloudinary.com/images/q_auto,f_auto/gigs/290414739/original/92ff23f0734314bd73211ac89798eaa286b756ea/do-python-programming-projects-in-numpy-pycharm-pandas-jupyter-notebook.png)]()
<!-- [![N|Solid](https://cdn-images-1.medium.com/max/1200/1*6j17ZDuywkKu7TOa2yvAKg.png)]() -->
###### TOOLS USED
- PYHTON - Jupyter Notebook
- mongoDB - (client)
- PostgreSQL - (client)
###### PYTHON MODULES USED
- pandas
- sodapy
- pymongo
- sqlalchemy
- psycopg2
- nbimport
- numpy
- SciPy
- seaborn
- matplotlib

> In this case study below research questions are identified and provided the results:


# WORK FLOW
[![N|Solid](https://github.com/JanushPrajosh/Dap_Team_Project/blob/main/workflow.png)]()

## STEPS TO BE PERFORMED 
##### 1 We are retrieving the datasets through API call i.e HTTP request and storing the retrived unstructured json dataset to the MongoDB client machine

>Dataset 1 - Dataset-1_Push_to_MongoDB.ipynb<br />
>Dataset 2 - Dataset-2_Push_to_MongoDB.ipynb<br />
>Dataset 3 - Dataset-3_Push_to_MongoDB.ipynb<br />

##### 2 We are importing the unstructured json dataset from the MongoDB client machine and performed below mentioned steps and exporting it in to the POSTGRESQL
###### ETL Process such as: Data extraction, Data cleaning, Pre-processing, Loading, Transforming, Data visualization

>Dataset 1 - Dataset-1_ETL&Visualisation.ipynb<br />
>Dataset 2 - Dataset-1_ETL&Visualisation.ipynb<br />
>Dataset 3 - Dataset-1_ETL&Visualisation.ipynb<br />


##### 3 Pulling structured datasets from postgresql and merging all the datasets using inner joint and visualizing and storing the merged resultant dataset in PostgreSQL 
###### ETL Process such as: Data extraction, Data cleaning, Pre-processing, Loading, Transforming, Data visualization
> Merging dataset 1 and 2 - MERGED_RESULTANT_DATASET_1.ipynb<br />
> Visualzing the dataset 2 and 3 - Visualizing_Resultant_Dataset.ipynb<br />

## MASTER_DO_NOTEBOOK
##### When we run the MasterFile.ipynb file we can see all the results and visualization. This handle separate files of an overall task. This file will run all the files sequentially and gives the visualized result of all the jupyter notebook files
> MasterFile.ipynb

Note: Run the MasterFile.ipynb file to run all the files sequentially and see all the results and visualization. This shows the outcome and their visualizations
