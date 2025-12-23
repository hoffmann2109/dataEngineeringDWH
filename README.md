# Setup steps
* Clone the project and open in your IDE
* Install libraries
  * pandas
  * numpy
  * sqlalchemy
  * dotenv
* Create a file `.env` and copy the following values and enter your credentials
  * db_user = postgres
  * db_password = <YOUR_PASSWORD>
  * db_host = localhost
  * db_port = 5432
  * db_name = <YOUR_DB_NAME>
* Copy the files into the data folder
  * articles.csv
  * customers.csv
  * open-meteo.csv (<-- Rename this file to this!)
  * transactions.csv
* Run the ETL-script!
* Execution on my Laptop takes approximately 18 Minutes.