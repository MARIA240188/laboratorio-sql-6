# laboratorio-sql-6
laboratorio-sql-6

We have just one item for each film, and all will be placed in the new table. For 2020, the rental duration will be 3 days, with an offer price of 2.99€ and a replacement cost of 8.99€ (these are all fixed values for all movies for this year). The catalog is in a CSV file named films_2020.csv that can be found at files_for_lab folder.

Instructions
Add the new films to the database.
Update information on rental_duration, rental_rate, and replacement_cost.
Hint
You might have to use the following commands to set bulk import option to ON:
show variables like 'local_infile';
set global local_infile = 1;
If bulk import gives an unexpected error, you can also use the data_import_wizard to insert data into the new table.
