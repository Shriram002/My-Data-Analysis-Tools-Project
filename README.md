# Understand Data Merging through Pandas: This Article Analyzes Lab 6 for Comprehensive Understanding

Short Description
A lab assignment within this repository shows Pandas data merging abilities to students who are part of the Data Analytics Tools course. Students learn basic merge types including one-to-one, one-to-many and multi-table procedures besides practical implementations such as financial data identification, movie data tagline enrichment and genre-specific movie filtering and actor list cross-comparison through outer joins.

Getting Started
Prerequisites
- Python 3.x users need to check for the installation of a suitable Python version.
- The recommended version for Pandas is 1.x.
- Jupyter Notebook (Optional): For an interactive coding environment.

Installing
1. Clone the Repository:


2. Install the Required Libraries:

Open the repository directory then install Pandas through the command line.


3. Ensure Data Files Are Available:

The necessary CSV files (wards.csv, Census.csv, movies.csv, financials.csv, taglines.csv, movie_to_genres.csv, iron_1_actors.csv, iron_2_actors.csv) must be placed either in the same directory as the code or their paths should be adjusted.

Running the Tests

Breakdown of Tests
- Data Loading and Validation:
The code utilizes pd.read_csv() functions to import several CSV files and verifies correct data loading through .head() previews.
- Merge Operations:

. The test group performs a one-to-one merge operation between wards.csv and Census.csv through the ward column with matching suffixes and also without suffixes.

. The merge operation between wards.csv and licenses.csv occurs using the ward column for a one-to-many relationship.

. The examples show how to perform chained merge operations between multiple datasets ranging from three to four tables.

- Practical Application Tests:

. A left join between movies.csv and financials.csv represents the identification of empty data entries in the budget column using the .isnull().sum() process.

. Taglines data enrichment demonstrates the differences between left join and inner join effects against movies.csv and taglines.csv data tables.

. The database application combines Science Fiction filtered movie genres from movie_to_genres.csv with movies.csv to yield complete movie information.

. The combination of an outer join between iron_1_actors.csv and iron_2_actors.csv enables the creation of an index which identifies actors appearing in just one film.

# Deployment
The project functions for educational purposes only. To run the code:

1. Open the Project:
Begin by opening the provided Jupyter Notebook or Python script within your preferred IDE.

2. Verify File Locations:
Check the CSV files are located in the correct directory or modify the file path in the code direction.

3. Run the Code:
Multiple merge operations with data validation results will become visible after you execute the cells or run the script sequentially.

# Author
Shriram Yadav
Data Analytics Tools – Durham College

# License
The project operates under the MIT License.

# Acknowledgement
- The authors offer their gratitude to Durham College along with the course instructors who made this lab assignment possible.

- Thank you to the open-source community which developed Pandas along with other resources vital for completing this project.
