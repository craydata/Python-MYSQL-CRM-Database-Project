## Python/Mysql CRM Database Project
This project is an implementation of a customer relationship management (CRM) database using Python and MySQL. It includes four tables for contacts, accounts, opportunities, and quotes, with relationships between them similar to those in Salesforce. The tables are prepopulated with thousands of records for analysis.

### Setup
- Install Python and MySQL on your local machine.
- Clone the repository to your local machine.
- Create a virtual environment for the project using venv or conda.
- Install the required packages listed in requirements.txt.
- Create a MySQL database and import the SQL file crm_database.sql to create the tables and populate them with records.
- Update the connection details in config.py to match your MySQL database credentials.

### Usage
The project contains Python scripts to perform data analysis on the CRM database. These scripts can be run from the command line or a Jupyter Notebook.

- queries.py: contains SQL queries to answer various questions about the CRM data.
- visualizations.py: uses the matplotlib and seaborn libraries to create visualizations for the SQL query results.
- main.py: runs all queries and visualizations and outputs the results to a Jupyter Notebook.
- config.py: contains the database connection details.

### Questions Answered
Here are some of the questions that can be answered using the SQL queries provided in this project:

- What is the total number of contacts for each account?
- How many contacts are there for each job title?
- Which contacts have the most opportunities associated with them?
- Which contacts have the most quotes associated with them?
- What is the average opportunity amount and quote amount for each contact?

### Visualizations
The project uses matplotlib and seaborn libraries to create visualizations for the SQL query results. The visualizations include:

Bar charts to show the number of contacts per account, per job title, and per contact for opportunities and quotes.
Grouped bar charts to show the average opportunity amount and quote amount for each contact.

### Future Work
This project can be expanded in several ways, including:

Adding more tables and relationships to the database.
Adding more queries to answer additional questions about the data.
Adding more visualizations to explore different aspects of the data.
Adding machine learning models to predict customer behavior and sales outcomes.





## Additional Questions
Contacts:

- How many contacts are associated with each account?
- What is the distribution of contacts by job title?
- Which contacts have the most opportunities associated with them?
- Which contacts have the most quotes associated with them?
- What is the average amount of opportunity and quote associated with each contact?

Accounts:

- Which accounts have the most opportunities associated with them?
- Which accounts have the most quotes associated with them?
- What is the distribution of accounts by industry?
- What is the average amount of opportunity and quote associated with each account?
- What is the average time from opportunity creation to close for each account?

Opportunities:

- What is the distribution of opportunity amounts?
- What is the average time from opportunity creation to close?
- What is the win rate for each stage of the sales process?
- Which opportunities have the highest amount of quotes associated with them?
- What is the average number of contacts associated with each opportunity?

Quotes:

- What is the distribution of quote amounts?
- Which opportunities have the highest amount of quotes associated with them?
- What is the average discount rate for each opportunity?
- What is the average time from quote creation to close?
- Which quotes were accepted and which were rejected?
