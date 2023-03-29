# Streamlined-Data-Ingestion-with-pandas 

## Discription
This course teaches you how to build pipelines to import data kept in common storage formats. You’ll use pandas, a major Python library for analytics, to get data from a variety of sources, from spreadsheets of survey responses, to a database of public service requests, to an API for a popular review site. Along the way, you’ll learn how to fine-tune imports to get only what you need and to address issues like incorrect data types. Finally, you’ll assemble a custom dataset from a mix of sources.
### Chapters 1 and 2 Importing Data from Flat and Excel Files
* `read_csv()` and `read_excel`
* Setting data types, choosing data to load, handling missing data and errors
* **`usecols`**, **`nrows`**, **`skiprows`**, **`names`**, **`dtype`**, **`na_values`**, **`.isna()`**, **`sheet_name`**, **`parse_dates`**(for standard datetime), **`pd.to_datetime()`**(Parse non-standard date formats)
* Putting multiple spreadsheets together (Using iterate through dataframe in dictionary)
* Setting custom true/false values
### Chapter 3 Importing Data from Databases
* `read_sql()` and `sqlalchemy`
* SQL `SELECT`, `WHERE`, aggregate functions and joins
* **`Install SQLite and import .db in it`**
* sqlalchemy's **`create_engine()`** makes an engine to handle database connections
### Chapter 4 Importing JSON Data and Working with APIs
* `read_json()`, `json_normalize()`, and `requests`
* Working with APIs and nested JSONs
* Appending and merging datasets
* **`requests.get()`**(get the data from API), **`.json()`**(extract JSON data), **`.append()`**, **`.merge()`**
