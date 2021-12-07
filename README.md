# database-project

## To set up

The web app is hosted locally, the user would need an MAMP server running locally. 
After the environment is setup, the user should download the csv file and application_data.scv and all the SQL files from the submission and build the mega table first by running build_mega_table.sql. Please make sure to use the correct path to the csv file on line 138. After that, 
Run the table creation script: proj2-table-creations.sql.
Run run proj2-SP.sql, proj2-views.sql, and proj2-SP.sql. 
Place the front_end directory containing the .php, .html, and .js files into the appropriate MAMP directory. 
Change the username, password, and port number in front_end/conn.php to match the local configuration.
Go to localhost:{Apache Port}/front_end/index.html to use the application. Note that Apache Port is likely a config in the MAMP client. This is not the SQL port.

## Technologies
PHP
HTML
CSS
JavaScript
