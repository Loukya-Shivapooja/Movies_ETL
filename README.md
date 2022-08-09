# Movies_ETL
## Purpose
### Background
Data Pipeline process known as Extract, Transform and Load. ETL is a workforce for moving data between database
Raw data exists in multiple places and forms. In order to perform any kind of data analysis, this data needs to be cleaned and structured. Data pipeline process ETL – Extract, Transform, and Load is a core concept in data engineering, ensuring that data is consistent, maintains its integrity, and nontheless strives for automatization of data wrangling. Without a consistent and robust data structure, it’s nearly impossible to perform any meaningful analysis.
### Project Overview 
A video streaming company, Amazing Prime decided to sponsor a hackathon, where participants trying to predict which low budget movies being released will become popular. Participants of a hackathon need a clean data in order to perform analyses for their algorithms. In order to provide organized and clean dataset, this project focuses on ETL **(Extract, Transform and Load)** process and includes the following:
* **Extracting** data from two different sources.
  * web scrape of Wikipedia website for all movies released since 1990
  * Data from Kaggle website for rating data.
* **Transforming** data using Jupyter Notebook, Python, Pandas and Python RegEx module.
* **Loading** data using PostgreSQL and pgAdmin to host final cleaned data set.
![image](https://user-images.githubusercontent.com/107584361/183774632-2712477c-0dfc-4f78-8287-58be6f1aed2b.png)
### Resources
Data Sources:
* Wikipedia web scrape **JSON file**
* Kaggle data from **Kaggle.com** - two files: `movies_metadata.csv` and `ratings.csv`
