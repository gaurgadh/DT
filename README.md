Overview
This repository contains Python scripts designed to analyze video game sales data. The primary focus is on calculating and comparing average global sales before and after the year 2005, as well as labeling records accordingly.

Getting Started
To set up and run the project, follow these steps:

Prerequisites
Ensure you have the following installed:

Python
Pandas
pymysql
sqlalchemy
Installation
Clone this repository to your local machine.
If you’re using analyze_sales.py, modify the database connection string to connect to your MySQL database.
If you’re using analyze_sales_csv.py, make sure the CSV file named vgsales.csv is available in the same directory as the script.
Running the Tests
Execute either of the Python scripts (analyze_sales.py or analyze_sales_csv.py). Both scripts will output the average global sales before and after 2005, along with a statement indicating which period had higher average sales.

Breakdown of Tests
Connect to the database (if using analyze_sales.py).
Load data from CSV (if using analyze_sales_csv.py).
Calculate average sales before and after 2005.
Label records as ‘pre-2005’ or ‘post-2005’.
Deployment
If applicable, provide instructions on deploying your project to a production environment.

Author
This analysis was conducted by Gaurav and Diksha.

License
The project is released under the MIT license.

Acknowledgment
We extend our gratitude to Professor Omar Al Trad for providing the dataset used in this analysis for educational purposes in the course “Data Analytics Tools.

