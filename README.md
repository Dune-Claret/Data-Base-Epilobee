# Data-Base-Epilobee
Computational project : analysis of the [EPILOBEE dataset](https://data.europa.eu/euodp/en/data/dataset/honey-bee-seasonal-mortality-2012-2014-epilobee-analysis).

- IGI-3014-CLARET.sql : the database and tables were created directly on the phpMyAdmin site using the tools on the site, then the SQL code of creation was retrieved and save as .sql.

- requete.ipynb : used to generate SQL queries to feed the tables thanks to the dataframe.

Then, we had to create an excel file for each table, gathering the data we wanted to use. In addition, in the same way as for the first case, we formatted the

data directly on excel, see above: The data has been formatted to be able to feed the database.
Once this step was done, we could import this file in the corresponding table, however, due to a size problem, we could only import about 1000 samples per table, our database containing about 5000 samples.
