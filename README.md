# ETL movies

# BACKGROUND

Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

![image](https://user-images.githubusercontent.com/86340630/129513778-2662a025-4af8-4ac5-8456-290642081518.png)

# OVERVIEW OF PROJECT

Wikipedia has a ton of information about movies, including budgets and box office returns, cast and crew, production and distribution, and so much more. Luckily, one of Britta's coworkers created a script to go through a list of movies on Wikipedia from 1990 to 2018 and extract the data from the sidebar into a JSON. Unfortunately, her coworker can't find the script anymore and just has the JSON file. We'll need to load in the JSON file into a Pandas DataFrame.

![image](https://user-images.githubusercontent.com/86340630/129514209-7a9a7d5b-0426-4cf6-b7a1-bdacfd71db67.png)

# PROJECT DELIVERABLES

1.	Deliverable 1: Write an ETL Function to Read Three Data Files
2.	Deliverable 2: Extract and Transform the Wikipedia Data
3.	Deliverable 3: Extract and Transform the Kaggle Data
4.	Deliverable 4: Create the Movie Database
5.	Deliverable 5: A written report on the Movie Database analysis README.md

# RESULTS WITH DETAIL ANALYSIS

1.	An ETL function is written to read in the three data files.
# Image
![image](https://user-images.githubusercontent.com/86340630/129537055-c4d57cc4-4e45-41fe-a3cb-6eb6098a93f6.png)

2.	The function converts the Wikipedia JSON file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file.
# Image
![Captura de pantalla (647)](https://user-images.githubusercontent.com/86340630/129522495-645308ee-62e8-4024-99aa-18d385aa5ebf.png)

3.	The function converts the Kaggle metadata file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file.
# Image
![Captura de pantalla (645)](https://user-images.githubusercontent.com/86340630/129520318-308e9c25-2af0-4bce-9895-bb5e55d83eb4.png)

4.	The function converts the MovieLens ratings data file to a Pandas DataFrame, and the DataFrame is displayed in the ETL_function_test.ipynb file.
# Images

![image](https://user-images.githubusercontent.com/86340630/129524657-6a461558-d5bd-4c9f-aa46-d645d79c1367.png)

![image](https://user-images.githubusercontent.com/86340630/129525096-1a55a708-9b90-405c-97bc-0761a55df8fb.png)

![image](https://user-images.githubusercontent.com/86340630/129525115-a87315eb-9ab5-4646-a8ee-c9c63030dfda.png)

![image](https://user-images.githubusercontent.com/86340630/129525129-1afa01e5-810c-469b-8bcb-87496e17822e.png)
































