### Project Overview: Analyzing International Student Test Scores and Socioeconomic Data of Chicago

#### 1. **Introduction**
This project aims to work with two different datasets: one containing international student test scores and another covering the socioeconomic data of various communities in Chicago. The project leverages Python and SQLite for database management and data analysis, and Seaborn for data visualization.

#### 2. **Setting Up the Environment**
The project begins with setting up a SQLite database environment using the `sqlite3` module in Python. The datasets are imported into the SQLite database, which is then queried for analysis.

#### 3. **International Student Test Scores**
- **Table Creation and Data Insertion:** 
  - A table named `INTERNATIONAL_STUDENT_TEST_SCORES` is created in the SQLite database to store the data related to international student test scores.
  - The table has four columns: `country`, `first_name`, `last_name`, and `test_score`.
  - Data for 99 students from various countries, including their test scores, is inserted into this table.

- **Data Queries:**
  - The project performs queries to retrieve data specific to certain countries. For example, a query to fetch all student records from Canada is executed.
  - A distribution of test scores is generated, grouping the scores by frequency. This distribution is then visualized using a bar plot.

#### 4. **Socioeconomic Data of Chicago**
- **Loading the Data:**
  - A CSV file containing socioeconomic data for different communities in Chicago is imported into a table named `chicago_socieconomic_data` within the SQLite database.

- **Data Exploration:**
  - The project involves querying the database to explore various aspects of the socioeconomic data. Examples include:
    - Counting the total number of rows (communities) in the dataset.
    - Counting the number of communities with a hardship index greater than 50.
    - Determining the maximum hardship index and identifying the community associated with this index.

- **Advanced Queries:**
  - The project explores more complex SQL queries, such as:
    - Fetching the community area with the highest hardship index.
    - Identifying communities with a per capita income greater than $60,000.

- **Visualization:**
  - A scatter plot is created to visualize the relationship between per capita income and hardship index for various communities in Chicago. This helps in understanding how income levels are correlated with the hardship experienced in different areas.

#### 5. **Conclusion**
This project demonstrates the use of SQLite for managing and querying datasets, and Python libraries such as Pandas and Seaborn for data manipulation and visualization. Through this project, we gain insights into the test score distribution of international students and the socioeconomic disparities among Chicago's communities.

### Key Learnings:
- Efficient use of SQL for data manipulation and extraction.
- Visualization of data distributions and correlations to extract meaningful insights.
- Understanding the socioeconomic dynamics of different communities in Chicago.

This project could be further expanded by integrating additional datasets or performing more complex statistical analyses on the data.
