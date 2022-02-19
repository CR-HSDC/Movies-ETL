# Movies-ETL

# Deliverable 1:

## Write an ETL Function to Read Three Data Files

**Requirement:**
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.

**Source File:**
ETL\_function\_test.ipynb

# Deliverable 2:
## Extract and Transform the Wikipedia Data

**Requirement:**
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

**Source File:**
ETL\_clean_wiki\_movies.ipynb


# Deliverable 3:
## Extract and Transform the Kaggle data

**Requirement:**
Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

**Source File:**
ETL\_clean\_kaggle\_data.ipynb

# Deliverable 4:#
## Create the Movie Database

**Requirement:** Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.

**Source File:** 
ETL\_create\_database.ipynb
