## Project title
Simple script for validating files in the DB by their size.

## How to use
* Import provided DB (lux.sql) or create your own
* Update scalars at the top:
- $maxSize = max size that will be used as the control sum, provided in gigabytes (4.7 is the default);
- $maxFileSize = leave untouched, turns your $maxSize into bytes;
- $query = sql query to be executed;
- $dsn = DBI Data Source Name, "DBI:%database_type%:%database_name%";
- $user = username to use;
- $password = password to use.
* Run as a Perl script or use bash to run it.

yozzik
