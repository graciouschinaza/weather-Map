Weather Data ETL Pipeline

Project Overview

This project is a simple ETL (Extract, Transform, Load) pipeline built using real-time weather data from the OpenWeather API.

The purpose of the project is to demonstrate how weather data can be extracted from an API, cleaned and transformed using Python and Pandas, and stored as a CSV file for analysis.

Data Source

The data was collected from the OpenWeather API.

The API provides real-time weather information for different cities.

For this project, weather data was collected for:

- Aba
- Onitsha
- Warri

The following information was collected:

- City Name
- Temperature
- Humidity
- Weather Condition
- Wind Speed
- Date and Time

ETL Process

1. Extract

Weather data was extracted from the OpenWeather API using Python and the Requests library.

The API was accessed using an API key, and weather information was collected for three cities.

2. Transform

The extracted data was converted into a Pandas DataFrame.

The data was then cleaned and prepared for analysis by:

- Checking for missing values
- Checking for duplicate records
- Checking data types
- Converting the Date and Time column to datetime format
- Renaming columns for easier use
- Organizing the data into a structured format

3. Load

After transformation, the cleaned weather data was saved as a CSV file named:

"weather_data_cleaned.csv"

This file can be used for future analysis.

Tools Used

The following tools and technologies were used:

- Python – Programming language used to build the ETL pipeline
- Pandas – Used for data transformation and analysis
- Requests – Used to connect to the OpenWeather API
- Google Colab/Jupyter Notebook – Used to write and execute the Python code
- OpenWeather API – Source of the real-time weather data
- CSV – Used to store the processed dataset

Steps Taken

1. Created an OpenWeather API account.
2. Generated an API key.
3. Connected Python to the OpenWeather API.
4. Extracted weather data for Aba, Onitsha, and Warri.
5. Selected the required weather fields.
6. Converted the extracted data into a Pandas DataFrame.
7. Checked for missing values.
8. Checked for duplicate records.
9. Checked and converted data types where necessary.
10. Renamed columns for easier use.
11. Saved the cleaned dataset as a CSV file.
12. Compared temperatures across the three cities.
13. Identified the city with the highest humidity.
14. Compared weather conditions across the cities.

Key Findings

The analysis focused on three main areas:

Temperature Comparison

The temperatures of Aba, Onitsha, and Warri were compared to identify the hottest and coolest city at the time the data was collected.

Humidity Analysis

The humidity levels of the three cities were compared to identify the city with the highest humidity.

Weather Conditions

The weather conditions reported for each city were compared to understand the differences in current weather conditions.

Project Output

The project produces the following output:

- Raw weather data extracted from the API
- Cleaned Pandas DataFrame
- Processed CSV dataset
- Basic weather analysis
- ETL pipeline source code

What I Learned

Through this project, I learned how to:

- Work with an API using Python
- Extract real-time data
- Use Pandas to organize and transform data
- Clean a dataset before analysis
- Save processed data as a CSV file
- Perform basic data analysis
- Understand the practical workflow of an ETL pipeline

Conclusion

This project demonstrates a basic ETL workflow where real-time weather data is extracted from an API, transformed using Python and Pandas, and loaded into a CSV file for analysis.

It provided practical experience in working with APIs, data transformation, data storage, and basic data analysis.
